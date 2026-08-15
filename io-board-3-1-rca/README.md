# 3.1 Channel IO Board for RCA
[Home](../README.md)

3 input and 1 output RCA board for routing audio signals

## Table of contents
- [Overview](#overview)
- [PCB Specifications](#pcb-specifications)
- [Circuit Diagram Switch Logic](#circuit-diagram-switch-logic)
- [Circuit Diagram Left Channel](#circuit-diagram-left-channel)
- [Circuit Diagram Right Channel](#circuit-diagram-right-channel)
- [BOM](#bom)

## Overview
[![PCB Front](./docs/pcb-front.thumb.png)](./docs/pcb-front.png)
[![PCB Back](./docs/pcb-back.thumb.png)](./docs/pcb-back.png)
- Designed for 5V DC operation
- 3 input RCA connections with indicator LEDs
- 1 output RCA connection with indicator LED
- Both signal and ground are switched on RCA boards to prevent ground loops between digital devices
- Minimize wire length for small signals
- Maximize signal to noise ratio
- RFI/EMI shield integrated into the PCB
- Through-hole connections for easy assembly and maintenance

## PCB Specifications
- Size: 115mm x 65mm
- Thickness: 2.0mm
- Material: FR4 S1000H TG150
- Layers: 4
- Finish: Immersion Gold (ENIG)
- Copper weight: 1oz
- Solder mask: Matte black
- Silkscreen: White

## Circuit Diagram Switch Logic
[![Circuit Diagram Switch Logic](./docs/circuit-diagram-switch-logic.thumb.png)](./docs/circuit-diagram-switch-logic.png)

## Circuit Diagram Left Channel
[![Circuit Diagram Left Channel](./docs/circuit-diagram-left-channel.thumb.png)](./docs/circuit-diagram-left-channel.png)

## Circuit Diagram Right Channel
[![Circuit Diagram Right Channel](./docs/circuit-diagram-right-channel.thumb.png)](./docs/circuit-diagram-right-channel.png)

## BOM
|Type|Quantity|Value|Description|
|----|--------|-----|-----------|
|RESISTOR|4|270Ω|Current limiting resistors|
|RESISTOR|4|1kΩ|Gate-stop resistors|
|RESISTOR|4|10kΩ|Pull-down resistors|
|CAPACITOR|1|KEMET 220uF/16V|Reservoir Capacitor|
|CAPACITOR|4|100nF Ceramic Disk|Decoupling Capacitor|
|LED|4|3mm|White Indicator LEDs|
|MOSFET|4|BS170|Signal switching|
|RELAY|8|OMRON G6K-2|Signal switching|
|DIODE|8|1N4148|Flyback diodes|
|ZENER|4|BZX55C5V1|Protection diodes|
|ZENER|8|BZX55C15|Protection diodes|
|CONNECTOR|4|RCA White|Signal connectors|
|CONNECTOR|4|RCA Red|Signal connectors|
|CONNECTOR|2|SMA|Signal connectors|
|CONNECTOR|1|JST PH4P ST90|Control connector|
|CONNECTOR|1|2x5 header|Control connector|
|STANDOFF|4|3mm x 2mm|LED standoff|
