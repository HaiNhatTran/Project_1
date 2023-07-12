# TEMPERATURE - HUMIDITY MONITORING SYSTEM USING WEB AND ESP8266

Purpose
Design a monitoring and throttling IoT system that has the following capabilities:
  - Manage temperature and humidity information.
  - Store temperature and humidity information on the Website.
  - Temperature and humidity monitoring: The system will collect temperature and humidity data from sensors and record these values.
  - Online data display: The system uses a web interface to display the collected temperature and humidity data.

Research content:
  - Learn and master the communication of ESP8266 NodeMCU.
  - Learn and communicate with the temperature - humidity sensor DHT11.
  - Using Wifi wireless technology.
  - Firebase communication with Web and Arduino IDE.
  - Design a temperature-humidity monitoring system with data update time according to the requirements given and controlled.
    
# System Design, Architecture, and Performance

                    System block diagram
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/ea39adb2-fad5-44fb-a343-c117e7cb2a81)

                    Web Connection Diagram – Firebase – ESP8266
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/eb1f1f27-32f9-4598-93cb-874dfad9dbf2)

                    Esp8266 connection diagram with DHT11 sensor
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/e9ac14ec-d78e-4e89-a02a-c6ef9e8e42a4)

                    Esp8266 connection diagram with Relay
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/234ed541-7326-4385-96b9-bb80da6c13f3)

                    Principle diagram of ESP8266
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/8d8609e9-96c7-45d5-89d5-f136d095b40a)

                    Algorithm flowchart for hardware
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/be0df506-45cc-4c1d-bad0-5e5849d74231)

                    System model after assembly
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/0d8c7470-0a8c-4d6e-9006-9fc13b279e5c)

                    Web model display and control
![image](https://github.com/HaiNhatTran/Project_1/assets/138964614/4ea7fa2d-5c2c-4193-b3db-d9f9193a5312)


# Conclude
    The set requirements have been fulfilled through stable and accurate operation circuit. 
    We already know the communication between the ESP8266 microcontroller with DHT11 and Relay sensors, and also know the principle of switching on and off of peripheral devices through Relay. 
    The information section is displayed through the website. 
    The website is designed with easy adjustments for users. 
    The system model uses Wifi wireless network and connects to Firebase to help monitor and update information easily, conveniently and quickly.

# Development
    • The current model is only a test system but can be easily applied in real life.
    • The monitoring components in the system are quite few, in the future I will try to integrate other sensors to be able to monitor the most optimal conditions.
    • Disseminate this smart model to rural areas, in order to improve people's understanding, access to technology and help reduce unnecessary incident damage.
