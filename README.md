# Vosk Listener with MQTT<a href="https://www.ohioiot.com"><img src="https://www.ohioiot.com/logo_150.jpg" width="40" ></a>

##### [(back to the Voice Controls organization page)](https://github.com/OhioIoT-Voice-Controls)

This code was generated in the linked YouTube video about making a speech-to-text voice assistant on a Raspberry Pi with a USB mic and MQTT.  See more at: [Offline Voice Control With MQTT](https://youtu.be/_ERvoHMBDac)

## Installation
Works on Git Bash on Windows.  The code picks up the default mic.  On a Windows laptop, this will be your laptop mic unless you have plugged a different one in.  On RPi, this will be any USB mic that you have plugged into the port:
```
git clone https://github.com/OhioIoT-Voice-Controls/Vosk-Listener-MQTT.git vosk-mqtt
cd vosk-mqtt
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
./+run
```

This code was a modification of the original program to run a Vosk listener without MQTT: [Vosk Listener](https://github.com/OhioIoT-Voice-Controls/Vosk-Listener).

## About
<a href="https://www.ohioiot.com"><img src="https://www.ohioiot.com/logo_150.jpg" width="40" ></a>

*OhioIoT is an IoT platform designed for small-scale IoT projects.  For more, check out our website at [www.OhioIoT.com](https://www.ohioiot.com).*
