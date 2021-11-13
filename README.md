# Open_Duco
Opensource firmware and hardware for Duco  Ventilation Boxes

Since I'm not happy with the functionallity of the Duco DucoBox Silent 400 m3/h I'm making an opensource version. (The general Quallity of these duco boxes is verry high and I would recommend them to everyone) But for a tech savy nerd not tech enough.

Goals of the project:
 - Measure Humidity in every air duct.
 - Measure Co2 in every air duct.
 - Measure Temperature in every air duct.
 - Wifi enabled by default
 - Fully controllable by Home assistant
 - If themperature outside < inside use the Duco System to cool the inside of my house.
 - Support 8 Sensors

The Open Duco Mini Is finally done! This is a drop in replacement for the Duco mainboard. 

# Open Duco Mini
![image.png](https://flamingo-tech.nl/wp-content/uploads/2021/11/image-5-1024x642.png)
 - Support for two sensors on the main board itself.
 - Wifi Support
 - Home assistant integration via ESPhome interface




# Progress:


|   Part:         |Done:	                         |Version:                       |Duco Part Number|Backwards compatible|
|----------------|-------------------------------|-----------------------------|-----------------------------|-----------------------------|
|Mainboard mini|✔️         |V1.1          | -|✔️ 
|MainBoard Pro         |❌|-|- |
|Moisture Sensor        |✔️            |V2.0        | 0000-4218 | ✔️|
|Co2 Sensor         |✔️|V2.1| 0000-4216 | ✔️
|All in one Sensor         |✔️|V2.1| - | ❌ 
|Programming cable         |✔️|V1.0| - | ✔️ 
|Secret Sensor         |❌|-| - | ❌
|Valve         |❌|-|- |


# Backwards Compatibility
If this is the awnser to this is yes, you can use the sensor in the original Duco Silent ventilation box.

# Important:
This project is not supported by Duco the company nor is there any affiliation to the company. Using these sensors will probably void duco's warranty.
