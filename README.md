# Vosk Listener with MQTT<a href="https://www.ohioiot.com"><img src="https://www.ohioiot.com/logo_150.jpg" width="40" ></a>

##### [(back to the Voice Controls organization page)](https://github.com/OhioIoT-Voice-Controls)

This code was generated in the linked YouTube video about making a speech-to-text voice assistant on a Raspberry Pi with a USB mic and MQTT.  See more at:
- [Video](https://youtu.be/_ERvoHMBDac)
- [Code Example](https://github.com/OhioIoT-Voice-Controls/Vosk-Listener)

## Installation
Just paste these commands to start your voice listener.  When you see `listening...`, it's working.  It works on Git Bash on Windows.  The code picks up the default mic:
```
git clone https://github.com/OhioIoT-Voice-Controls/Vosk-Listener-MQTT.git vosk-mqtt
cd vosk-mqtt
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
./+run
```
Edit the IP address on line xx of `listener.py` to match the IP address of the MQTT broker that you are running.  Then:
```
./+run
```


## About
<a href="https://www.ohioiot.com"><img src="https://www.ohioiot.com/logo_150.jpg" width="40" ></a>

*OhioIoT is an IoT platform designed for small-scale IoT projects.  For more, check out our website at [www.OhioIoT.com](https://www.ohioiot.com).*
