# Sm-ElectronicsRelay-ESP32

## Task 5: ESP32 with Light and Motion Sensors to Control Relay-Connected Light 

### Description
This repository uses an ESP32 with a light sensor and a motion sensor to control an LED based on the inputs from these sensors. The sensors' data are connected to a database, and the bulb's state changes according to the following conditions:

* When there is no light and there is motion, the LED turns on.
* When there is no light or motion, the LED turns off.
* If there is light and no motion, the LED turns off.

### Demo  
![esp32](https://github.com/user-attachments/assets/e778fe98-6dfe-4621-8767-d576aa89006f)
https://wokwi.com/projects/404132562546194433

### Components
  * ESP32
  * Relay module
  * Light sensor (LDR)
  * LED
  * Movement sensor (PIR sensor)

### Circuit Connections
#### 1- Relay Module 
  * VCC: Connect to 5V on ESP32
  * GND: Connect to GND on ESP32
  * IN: Connect to GPIO 4 on ESP32
  * COM (Common): Connect to a suitable power source
  * NO (Normally Open): Connect to anode of the LED

#### 2- LED
  * Anode (positive lead): Connect to relay NO (Normally Open)
  * Cathode (negative lead): Connect to GND on ESP32

#### 3- PIR Sensor


### Acknowledgments
https://randomnerdtutorials.com/esp32-pir-motion-sensor-interrupts-timers/
