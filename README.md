# What is Chrome Wi-Fi Decoder?
Chrome Wi-Fi Decoder is a simple batch script used to fetch passwords to Wi-Fi networks your computer has connected to in the past, built for Chrome OS.
# Requirements
* Developer mode must be enabled.
* You must have connected to the Wi-Fi network previously.
# Usage
1. Open your terminal.
2. Execute `shell`.
3. Execute `sudo find  /home/root/ -name shill.profile -exec cp {} /tmp/ ;`.
4. Execute `sudo chmod 644 /tmp/shill.profile`.
5. You will need to cd into your downloads or wherever the script is stored, `cd /home/chronos/user/Downloads/`
6. Execute `sh wifi.sh`
6. Profit.
