ECE_ESP32_PCB_Beltran_EN1B
 
Project Description
 
This project uses the ESP32 microcontroller to build a low-power, Wi-Fi-enabled sensor monitoring system. It reads data from various sensors (temperature, humidity, motion, etc.), processes the information locally, and sends it to a cloud platform or local dashboard via Wi-Fi. The system can also receive commands remotely, making it suitable for home automation, environmental monitoring, and IoT prototyping. It demonstrates core embedded systems concepts: digital/analog I/O, wireless communication, and real-time data handling.
 
Features
 
- Wi-Fi Connectivity: Connects to local network for data transmission and remote control

- Sensor Integration: Reads data from DHT11/DHT22 (temperature & humidity), PIR (motion), and analog sensors

- Data Logging: Stores readings locally or sends to cloud services (e.g., ThingSpeak, Blynk, MQTT broker)

- Low-Power Mode: Supports deep sleep to extend battery life for portable use

- GPIO Control: Controls outputs like LEDs, relays, or buzzers based on sensor input or remote commands

- Serial Monitoring: Real-time debug and data view via USB serial port

- OTA Updates: Optional over-the-air firmware updates
 
Components Used
 
- ESP32 Development Board (e.g., ESP32-WROOM-32, ESP32-DevKitC)

- Sensors: DHT11/DHT22 (temperature & humidity), PIR motion sensor, photoresistor (LDR)

- Outputs: LEDs, 5V relay module, buzzer

- Passive components: Resistors (220Ω, 10kΩ), jumper wires, breadboard

- Power supply: USB cable, 3.3V/5V power source, or Li-ion battery with charging module
 
Software Used
 
- Arduino IDE: Main development environment, with ESP32 board support package installed

- ESP-IDF: Optional official development framework from Espressif Systems

- Libraries:

-  WiFi.h  – built-in for Wi-Fi management

-  DHT sensor library  +  Adafruit Unified Sensor  – for DHT sensors

-  PubSubClient.h  – for MQTT communication

-  Blynk.h  /  ThingSpeak.h  – for cloud integration

- Tools: Serial Monitor, Board Manager, Library Manager
 
Author Name
 
[CHARLES BELTRAN]
 
Course & Section
 
[ECT, Embedded Systems / IoT Applications]
[IRREG/ ECE,]
 
 
 
