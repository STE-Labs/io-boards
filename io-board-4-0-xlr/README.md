# 4.0 Channel IO Board for XLR
[Home](../README.md)

4 input and 0 output XLR board for routing audio signals

## Table of contents
- [Overview](#overview)
- [PCB Specifications](#pcb-specifications)
- [BOM](#bom)

## Overview
- Designed for 5V DC operation
- 4 input XLR connections with indicator LEDs
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
|Resistor|4|100Ω|Current limiting resistors|
|Resistor|4|1kΩ|Gate-stop resistors|
|Resistor|4|10kΩ|Pull-down resistors|
|LED|4|3mm|Indicator LEDs|
|MOSFET|4|BS170|Signal switching|
|RELAY|8|OMRON G6D-2|Signal switching|
|DIODE|8|1N4148|Flyback diodes|
|ZENER|8|BZX55C15|Protection diodes|
|CONNECTOR|8|Neutrik NC3 MAV|XLR Input connectors|
|CONNECTOR|1|JST PH 4-PIN|Control connectors|
|CONNECTOR|1|2x5 header|Control connectors|
