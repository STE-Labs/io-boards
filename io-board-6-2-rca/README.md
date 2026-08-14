# 6.2 Channel IO Board for RCA
[Home](../README.md)

6 input and 2 output RCA board for routing audio signals

## Table of contents
- [Overview](#overview)
- [PCB Specifications](#pcb-specifications)
- [BOM](#bom)

## Overview
- Designed for 5V DC operation
- 6 input RCA connections with indicator LEDs
- 2 output RCA connections with indicator LEDs
- Both signal and ground are switched on RCA boards to prevent ground loops between digital devices
- Minimize wire length for small signals
- Maximize signal to noise ratio
- RFI/EMI shield integrated into the PCB
- Through-hole connections for easy assembly and maintenance

## PCB Specifications
![PCB Front](./docs/pcb_front.png)
![PCB Back](./docs/pcb_back.png)
- Size: 100mm x 70mm
- Thickness: 2.0mm
- Material: FR4
- Layers: 4
- Finish: Immersion Gold (ENIG)
- Copper weight: 1oz
- Solder mask: Matte black
- Silkscreen: White

## PCB Dimensions
![PCB Dimensions](./docs/pcb_dimensions.png)

## BOM
|Type|Quantity|Value|Description|
|----|--------|-----|-----------|
|Resistor|7|100Ω|Current limiting resistors|
|Resistor|7|1kΩ|Gate-stop resistors|
|Resistor|7|10kΩ|Pull-down resistors|
|LED|7|3mm|Indicator LEDs|
|MOSFET|7|BS170|Signal switching|
|RELAY|14|OMRON G6D-2|Signal switching|
|DIODE|14|1N4148|Flyback diodes|
|ZENER|14|BZX55C15|Protection diodes|
|CONNECTOR|8|RCA White|Signal connectors|
|CONNECTOR|8|RCA Red|Signal connectors|
|CONNECTOR|2|SMA|Signal connectors|
|CONNECTOR|1|JST PH 4-PIN|Control connectors|
|CONNECTOR|1|2x5 header|Control connectors|
