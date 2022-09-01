# Meteo station PCB based on ESP32

![image](img/pcb.jpg)
<p align="center">
  <img alt="Light" src="img/DSCF8146.jpg" width="48%">
&nbsp; &nbsp; &nbsp;
  <img alt="Dark" src="img/DSCF8181.jpg" width="48%">
</p>

### ◾ About the project

**Meteo station** is my small after-hours project that contains of three repositories:
- Meteo station PCB based on ESP32 (this repo)
- Meteo station code
- Meteo station 3D prints


> **Warning**
> This is a hobbyist project. I'm not an electronic engineer so I take no responsibility for any possible issues you may encounter :)


Gerber files for version 1.0 of Meteo Station is available [in the releases section](https://github.com/alicjamusial/meteo-station/releases/tag/release-1.0.0).

The board was designed using [KiCad](https://kicad.org/) (version: `6.0`).

I was inspired by solution created by [this guy on Instructables](https://www.instructables.com/Solar-Powered-WiFi-Weather-Station-V30/). He did a good job, so I strongly recommand exploring his meteo projects!

### ◾ Sensors & components
**Components:**
- ESP32 (ESP-WROOM-32) - main computer
- TP4056 - battery charger
- solar panel - I finally used DFRobot FIT0601 Monocrystalline Solar Panel (5V, 1A)
- 18650 battery + holder
- slide switch, LDO etc. - according to the KiCad project

**Sensors:**
- BME280 - humidity, pressure, temperature
- DS18B20 - temperature
- BH1750 - light (should be mounted on cables - outside of the box)

**Tools I used:**
- 3D printer to print a Stevenson cage and solar panel holder

**Other stuff that you'll need:**
- server (e.g. RaspberryPi) with Influx database and Grafana instance to gather data from the station and display it in a nice way

![schema](img/grafana.png)

### ◾ Useful tips

Lorem



### ◾ Adjust it to your needs!
This is an absolutely hobbyst project :) You can use it as a reference to create something loads better.


### ◾ License
Meteo Station PCB is available on Creative Commons Attribution Share Alike 4.0 International license (more in [license file](LICENSE.txt)). You are free to use it, modify it and produce as many of your own boards as you need :)


![schema](img/schematics.jpg)
![schema](img/schematics2.jpg)

### ◾ Final result

Cable tie and tape for the win ;)

<p align="center">
  <img alt="Dark" src="img/meteo-station.jpg" width="65%">
</p>
