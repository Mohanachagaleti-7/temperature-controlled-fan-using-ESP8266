# temperature-controlled-fan-using-ESP8266
This project is an IoT-based Temperature Controlled Fan using ESP8266, DHT11 sensor, and Blynk app. It continuously monitors room temperature and humidity and displays the data in real time on a mobile phone. When the temperature rises above 31°C, the fan turns ON automatically and turns OFF when it drops, saving energy and improving comfort.
#  Features
Automatic fan control based on temperature
Real-time temperature and humidity monitoring
Wireless data transmission using Wi-Fi
Mobile monitoring through Blynk app
Energy-efficient and low-cost solution
## Components 
 #🔧 Hardware Components:
ESP8266 (NodeMCU)--Acts as the main controller and Wi-Fi moduleSends sensor data to Blynk and controls the fan
DHT11 Temperature and Humidity Sensor--Measures room temperature and humidity
Relay Module--Used to switch the fan ON and OFF safely
DC Fan / AC Fan--Works as the cooling device
Connecting Wires (Jumper Wires)--Used for circuit connections
Power Supply--Provides power to ESP8266 and relay
#💻 Software Components:
Arduino IDE--Used to write and upload the code to ESP8266
Blynk Application--Displays temperature and humidity values
1(Libraries Used:
2)ESP8266WiFi.h
3)BlynkSimpleEsp8266.h
4)DHT.h

# Working Principle 
--> DHT11 reads temperature and humidity.
-->ESP8266 processes the sensor data.
-->Data is sent to the Blynk app via Wi-Fi.
-->If temperature > 31°C → Fan ON
-->If temperature ≤ 31°C → Fan OFF
