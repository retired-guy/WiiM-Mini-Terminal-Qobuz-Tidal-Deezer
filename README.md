# WiiM-Mini-Terminal-Qobuz-Tidal-Deezer
Simple client apps for Qobuz, Tidal and Deezer to play albums/playlists to WiiM Mini from Linux terminal.  Tested on ChromeOS and Raspberry Pi OS.

Modify wiim.ini file with your WiiM Mini's ip address, and copy to ~/.config/wiim/wiim.ini:

mkdir ~/.config/wiim

cp wiim.ini ~/.config/wiim

Make the files executable:

chmod +x wm?

Copy the files to local/bin directory:

cp wm? ~/.local/bin

Install Python requirement packages:

pip3 install -r requirements.txt

Tidal (wmt):
![photo](https://raw.githubusercontent.com/retired-guy/WiiM-Mini-Terminal-Qobuz-Tidal-Deezer/main/Screenshot%202022-09-09%202.05.41%20PM.png)

Qobuz (wmq):
![photo](https://raw.githubusercontent.com/retired-guy/WiiM-Mini-Terminal-Qobuz-Tidal-Deezer/main/Screenshot%202022-09-09%202.05.31%20PM.png)

Deezer (wmd):
![photo](https://raw.githubusercontent.com/retired-guy/WiiM-Mini-Terminal-Qobuz-Tidal-Deezer/main/Screenshot%202022-09-09%202.05.21%20PM.png)


