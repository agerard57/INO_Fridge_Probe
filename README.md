# INO_Fridge_Probe
An ESP-32 controller that sends a thermometer probe value to a WebApp instance

## Table of contents

- [Table of contents](#table-of-contents)
- [Detailled description](#detailled-description)
- [Components and supplies](#components-and-supplies)
- [Breadboard view](#breadboard-view)
- [Schematic view](#schematic-view)

## Detailed description

This project aims to make a system that regularly takes the temperature of a fridge with a probe and then sends said values using the ZigBee protocol to a receiver that will eventually transform and adapt the data for a web app.

## Components and supplies

- XIAO-ESP32-C6
- DS18B20 1-wire thermometer sensor
- 4.7K Resistor
- SunFounder 3-pin Button v2.0
- 16x2 QAPASS LCD w/I2C Module
- Breadboard
- Jumper wires

## Breadboard view

![image](https://user-images.githubusercontent.com/56207146/196478829-52e3ca05-d96d-4309-8e82-a4ba5c4ceeae.png)

## Schematic view

![image](https://user-images.githubusercontent.com/56207146/196470456-f2446f37-cc52-4c66-b142-ee55d017a498.png)
