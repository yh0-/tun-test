
DESCRIPTION: Bash program for launching airtun-ng to join OPEN/WEP access point by using raw ieee802.11 packet injection.

AUTHOR: Yahya Sjahrony <yysjryysjr AT gmail DOT com>

REFERENCES:

- OLD BackTrack3 Howtos: Using airtun-ng to monitor WLAN in real-time and be joined as a client via injection, http://www.backtrack-linux.org/forums/showthread.php?t=17183

- Airtun-ng WIKI, http://www.aircrack-ng.org/doku.php?id=airtun-ng

NOTES:
- Tested on Backtrack 5 R2/R3 Linux (kernel 3.2.6) with wireless cards: Realtek RTL8187L (rtl8187), Ralink 2573 USB (rt73usb) and Atheros AR9285 (ath9k). 

- All needed tools are already included in Backtrack except this script needs latest version of iw.

- Airtun-ng allows you to use a WEP encrypted network with a driver that supports injection, but no WEP encryption support.

- Surprisingly this solves 'Atheros AR9285 with ath9k driver unable to connect to Internet using WEP problem' on Backtrack 5 R2. 

- All credits go to Backtrack and Aircrack-ng forums and developers.
