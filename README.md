**IoT-Based Gas \& Smoke Detector with LPG Gas Level Monitoring**



**📌 Overview**

This project is an **IoT-enabled Gas and Smoke Detection System with LPG Gas Level Monitoring**.  

It provides early alerts in case of LPG leaks, smoke, or low gas levels using **sensors, NodeMCU ESP8266, and Blynk IoT cloud**.  



**Key features:**

\- Detects **LPG gas leakage** using an MQ-2 sensor.

\- Detects **smoke** from fire hazards.

\- Monitors **LPG cylinder gas level** using a load cell with HX711 ADC.

\- Provides **real-time notifications** on the Blynk mobile app.

\- Activates **buzzer, LED, DC motor, and servo motor** for safety actions.

\- Displays sensor readings on an **OLED display**.



---



** 🛠 Components Used**

\- **ESP8266 NodeMCU** – WiFi-enabled microcontroller  

\- **MQ-2 Sensor** – Detects combustible gases and smoke  

\- **Load Cell (5kg) + HX711 Amplifier** – LPG cylinder weight monitoring  

\- **OLED Display (0.96" I2C)** – Displays gas/smoke readings  

\- **Buzzer + LED Indicators** – Alert signals  

\- **DC Motor** – Water sprinkler for fire prevention  

\- **Servo Motor** – To turn off gas knob in emergencies  

\- **Power Supply \& Connectors**



---



**⚙️ Software Requirements**

\- **Arduino IDE** (for coding \& uploading firmware)  

\- **Blynk IoT App** (for monitoring and notifications)  

\- Required Libraries:

&nbsp; - `ESP8266WiFi.h`

&nbsp; - `BlynkSimpleEsp8266.h`

&nbsp; - `MQ2.h`

&nbsp; - `Adafruit\_GFX.h`

&nbsp; - `Adafruit\_SSD1306.h`

&nbsp; - `Servo.h`

&nbsp; - `HX711.h`



---



**📲 Features**

\- 🔔 **Real-time Alerts** – Sends notifications on gas leaks, smoke, or low LPG levels.  

\- 📉 **Gas Level Monitoring** – Tracks LPG cylinder capacity and notifies when below threshold.  

\- 🌐 **IoT Integration** – Uses **Blynk app** for mobile monitoring and control.  

\- 🚨 **Automatic Actions** – Triggers motor, servo, and alarm in emergencies.  

\- 📊 **Live Dashboard** – View readings on OLED and Blynk app.



---



**🔌 Circuit / Block Diagram**

The system integrates:

\- MQ-2 sensor → NodeMCU  

\- Load Cell + HX711 → NodeMCU  

\- Outputs (Buzzer, LED, DC motor, Servo) controlled by NodeMCU  

\- OLED Display for visualization  

\- Blynk app for remote monitoring  



---



 **▶️ Getting Started**

1\. **Hardware Setup**

&nbsp;  - Connect MQ-2, Load Cell, HX711, OLED, Buzzer, LED, Motor, and Servo to NodeMCU.

&nbsp;  - Ensure proper power supply.



2\. **Software Setup**

&nbsp;  - Install **Arduino IDE** and required libraries.

&nbsp;  - Update WiFi credentials and **Blynk Auth Token** in the code.

&nbsp;  - Upload the sketch to NodeMCU.



3\. **Mobile Setup**

&nbsp;  - Install **Blynk IoT App**.

&nbsp;  - Create a new project, add widgets (gauge, LED, notification).

&nbsp;  - Link with your **Blynk Template ID \& Auth Token**.



---


**📊 Results**

\- Successfully detected **gas leakage and smoke**.  

\- Automated **alert and prevention system** activated.  

\- Gas cylinder level monitoring worked with **real-time notifications**.  

\- Integrated with **Blynk mobile dashboard** for user convenience.  



---



**✅ Conclusion**

This project enhances **home and industrial safety** by combining **gas leak detection, smoke detection, and LPG monitoring** into one IoT system.  

It ensures **early warning, real-time monitoring, and automatic preventive actions** to minimize risks.  



---


**📚 References**

\- \[Blynk IoT Platform](https://blynk.io)  

\- \[ESP8266 Documentation](https://arduino-esp8266.readthedocs.io)  

\- MQ-2 Sensor Datasheet  



