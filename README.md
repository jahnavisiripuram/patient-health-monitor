# patient-health-monitor
This system allows users to keep track of their body
vitals like blood pressure
and heartbeat and remotely send
the data to attached mobile phone using a software called THINKSPEAK.
# COMPONENTS REQUIRED ARE
Arduino UNO Board	microcontroller	(1)	
LCD Display	16x2 LCD Display	(1)
Potentiometer	10K	(1)
ESP8266-01	Wifi Module	(1)
Pulse Sensor (1)
LM35	Temperature Sensor	(1)
Connecting wires	or jumper wire	(some)
Breadboard	Normal	(1)
2K Resistor	THT	(1)
1K Resistor	THT	(1)
LED 5mm (1) 
# Setting Up Thingspeak
ThingSpeak provides very good tools for IoT-based projects. The ThingSpeak website allows you to monitor data and control your system over the Internet using channels and web pages provided by ThingSpeak. Therefore, you must first log into ThingSpeak. Please access https:
Create an account at thingspeak.com.Then create a new channel and set up what you want. The tutorial in the video below. Follow the video for more clarification.

Then create the API keys. This key is required for programming modifications and setting your data.

Then upload the code to the Arduino UNO by assembling the circuit shown above. Open the serial monitor and it will automatically connect to Wi-Fi and set up everything.

Now click on channels so that you can see the online data streaming, i.e IoT Based Patient Health Monitoring System using ESP8266 & Arduino
