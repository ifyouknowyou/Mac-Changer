MAC Address Changer (Linux)

This is a simple Bash script to randomly change the MAC address of a wireless interface on Linux systems using macchanger.

⚙️ Requirements

Linux OS

macchanger installed

Root (sudo) privileges

Wireless interface (default: wlan0)

Install macchanger if not installed:

sudo apt update
sudo apt install macchanger

📥 Clone the Repository
git clone https://github.com/yourusername/mac-changer.git
cd mac-changer


Usage:

Make the script executable:

chmod +x mac_changer.sh


Run the script with sudo:

sudo ./mac_changer.sh

