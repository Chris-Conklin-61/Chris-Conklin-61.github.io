[Watch the Bees](http://admin:123456@kyserike.mynetgear.com:500/mjpeg/stream.cgi?chn=0)

# Project Overview

Honey Bees play an essential role in our ecosystem. Our food depends on their pollination activity. A world without pollinators would be devastating for food production. A couple of years ago I decided to do my part to help the declining honey bee population by creating my own apiary. I also wanted to use my electrical and computer engineering skills to aid in understand my bee colonies.

Inspired by some work that a colleague had previously done and a couple of web resources dealing with monitoring activity within the hive using a variety of electrical sensors, I’ve used some of my electrical engineering and computer knowledge to come up with my own Hive Monitoring system to better understand conditions within the hive without having to be physically at the apiary. 

The system monitors and records the weight of the hive, the ambient temperature and humidity at the hive location, and the
temperature and humidity within the hive. The readings are capture every minute and sent to “The Cloud” via a wifi connection
for display and analysis. Recently added to the system is a wifi camera. The complete Hive Monitoring system is also solar
powered so the battery health and solar production is also monitored.

![Hive Monitor Blynk Data Visulation](/images/HM_Blynk_1.PNG)

## What Are my Expectations ?

My hope is to be able to gather data from my honey bee hives and use it as a tool to better understand the health and activity
of the honey bee colony. It doesn’t replace going in periodically and physically inspecting the hives, but used as a tool it
can help to gain an extra set of eyes to see what’s going on inside without physical disturbing the colony.

## How do I think I can use the data?

### Weight
- Nectar Flow Indication and intensity.
- Winter Store Levels
- Foragers out and returning
- Swarming (Send Email / text alert / app notification)
- Robbing (Send Notification)

### Hive Temperature
- Health of the colony
- Brood

### Hive Humidity
- Indication of nectar 
- Indication of uncapped brood
- Indication of condensation issues (Winter)

### Other Sensors
- Microphone (Noise Levels / Sound Analysis)
- Temperature Sensor / per box
- Lux Sensor (measure sunlight intensity)
- Camera / Video
- Motion Detection

![Hive Monitor Blynk Data Visulation 2](/images/HM_Blynk_2.PNG)

## The Hardware

- Raspberry Pi 3+B Micro Computer
- Waterproof Box
- Waterproof Cable Connectors
- 12V-5V DC-DC Converter
- Sensors
  - DHT22 Temperature/Humidity (2)
  - HX711 Load Cell A/D Module (4)
  - 1NA219 DC Voltage/Current Sensor
- Scale
  - 50 kg Load Cell (4)
  - Table Leveling Feet (4)
  - 48”x2”x2” Angle Steel (3/16”)
  - 48”x2”x2” Flat Aluminum 3/16”)
- Miscellaneous
  - Project Boards (2)
  - Screw Terminals
  - screws
  - Wire
  
### Parts Diagram

Some parts are not available in Fritzing (Solar Panel, Solar Controller, Lead Acid Battey, and DC-DC Converter) but will be included with a later update. 
  
![Hive Monitor Fritizng Diagram](/images/Hive_Monitor_bb.jpg)

### Schematic
Solar power system is not included in the schematic

![Hive Monitor Schematic](/images/Hive_Monitor_schem.jpg)

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Chris-Conklin-61/Chris-Conklin-61.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
