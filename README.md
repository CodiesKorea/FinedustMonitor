# FinedustMonitor
* Fine dust monitoring device powered by NodeMCU. 

## Specifications
### Scenarios
* Measuring finedust contamination level in the air in a real time and display on a OLED Screen. 
* Measuring the current temperature
* Refining data and synchronize with the web-based cloud services. (e.g. ThingSpeak, Plaive) 

### Connections
1 x Micro-USB

### Wireless
IEEE 802.11 b/g/n Wi-Fi technology.

### Battery life 
* Up to 24 hours of typical device usage.

## Apparatus (Equipments)
### Platform
* ESP8266 NodeMCU

### SDS011 Dust Sensor
* Soldering required.
* D1 : TX of SDS011

### 0.96" I2C OLED Display 
* Soldering required.
* D3 : Data, D2 : Clock

### DS18820 Temperature Sensor (Thermometer)
* Soldering required.
* D4 : Data

### KOKIRI A-PACK FIXIE 5 (KP-LS50) Portable Battery
* Micro-USB : Power 
* Dimension : W (62.3 mm) × D (112.0 mm) × H (13.0 mm) 
* Input : DC-5V / 2A
* Output : DC-5V / 2.1A
* Capacity : 5000 mAh

### Data Refinement / Synchronization
* ThingSpeak (https://thingspeak.com/)
* Plaive (https://plaive.10make.com/)

### Drivers / References
Please install https://github.com/squix78/esp8266-oled-ssd1306
