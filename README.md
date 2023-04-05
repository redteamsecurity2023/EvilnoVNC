# EvilnoVNC
This is a phishing ready platform.  Unlike other phishing methods, EvilnoVNC allows you to bypass 2FA using a real browser via noVNC connection.  In addition, this tool allows us to see in real time all the victim's activities, access to downloaded files and the entire browser profile, including cookies, saved passwords, browsing history, etc.

EvilnoVNC is a Ready to go Phishing Platform.

Unlike other phishing techniques, EvilnoVNC allows 2FA bypassing by using a real browser over a noVNC connection.

In addition, this tool allows us to see in real time all of the victim's actions, access to their downloaded files and the entire browser profile, including cookies, saved passwords, browsing history and much more.

Requirements
Docker
Chromium
Download
It's recommended to clone the complete repository or download the zip file.
Additionally, it's necessary to build Docker manually. You can do this by running the following commands:

git clone https://github.com/JoelGMSec/EvilnoVNC
cd EvilnoVNC ; sudo chown -R 103 Downloads
sudo docker build -t joelgmsec/evilnovnc .
Usage
./start.sh -h
                                                     
  _____       _ _          __     ___   _  ____
 | ____|_   _(_) |_ __   __\ \   / / \ | |/ ___|
 |  _| \ \ / / | | '_ \ / _ \ \ / /|  \| | |
 | |___ \ V /| | | | | | (_) \ V / | |\  | |___
 |_____| \_/ |_|_|_| |_|\___/ \_/  |_| \_|\____|

  ---------------- by @JoelGMSec --------------

Usage:  ./start.sh $resolution $url

Examples:
        1280x720  16bits: ./start.sh 1280x720x16 http://example.com
        1280x720  24bits: ./start.sh 1280x720x24 http://example.com
        1920x1080 16bits: ./start.sh 1920x1080x16 http://example.com
        1920x1080 24bits: ./start.sh 1920x1080x24 http://example.com

Dynamic resolution:
        ./start.sh dynamic http://example.com

The detailed guide of use can be found at the following link:
https://darkbyte.net/robando-sesiones-y-bypasseando-2fa-con-evilnovnc

Features & To Do
 Export Evil-Chromium profile to host
 Save download files on host
 Disable parameters in URL (like password)
 Disable key combinations (like Alt+1 or Ctrl+S)
 Disable access to Thunar
 Decrypt cookies in real time
 Expand cookie life to 99999999999999999
 Dynamic title from original website
 Dynamic resolution from preload page
 Basic keylogger
 Replicate real user-agent and other stuff
License
This project is licensed under the GNU 3.0 license - see the LICENSE file for more details.

Credits and Acknowledgments
Original idea by @mrd0x: https://mrd0x.com/bypass-2fa-using-novnc
This tool has been created and designed from scratch by Joel Gámez Molina // @JoelGMSec

Contact
This software does not offer any kind of guarantee. Its use is exclusive for educational environments and / or security audits with the corresponding consent of the client. I am not responsible for its misuse or for any possible damage caused by it.

For more information, you can find me on Twitter as @JoelGMSec and on my blog darkbyte.net.

Support
You can support my work buying me a coffee:

buymeacoffe
