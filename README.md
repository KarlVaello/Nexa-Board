<p align="center">
  <img width="382" height="155" src="https://github.com/KarlVaello/Nexa-Board/blob/master/Other/Graphics/nexa_LOGO.png">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-brightgreen.svg">
</p>


### NOTES!

In need of satisfying the ISO 15765-2 the board will receive hardware changes.

ISO 15765-2, or ISO-TP (Transport Layer), is an international standard for sending data packets over a CAN-Bus. The protocol allows for the transport of messages that exceed the eight byte maximum payload of CAN frames. ISO-TP segments longer messages into multiple frames, adding metadata that allows the interpretation of individual frames and reassembly into a complete message packet by the recipient. It can carry up to 4095 bytes of payload per message packet.

Full duplex RS-485 will be replaced by CAN-bus.


### What is Nexa-Board?
Nexa-Board is an open source project, based on STM32F103 microcontroller with a full duplex RS-485 to create a multipoint network that allows receiving and sending the information of all the boards.
RS-485 as a physical layer and by programming you can set your own data exchange and interpretation protocol.

Hardware characteristics
-	72 MHz
-	Full duplex RS-485 fully configurable.
- CAN-BUS
-	17 GPIO pins
- 7 to 15 V power input
-	Power input polarity protection

### Why does it exist ?
Exist as a solution to get a fully configurable comunication protocol, that allow you to create your own protocol depending on your needs.

### Getting Started
- Get a Nexa Board

### Project that use Nexa-Board
- Nexa Home

### TODO ![status](https://img.shields.io/badge/Status-HW--Test-orange.svg)
- [x] Board design (Schematic)
- [x] Board design (PCB)
- [x] PCB manufacture
- [ ] HW test
- [ ] HW final version
---------------
- [ ] New hardware changes due to apply CAN-bus
- [x] Board design (Schematic)
- [x] Board design (PCB)
- [x] PCB manufacture
- [ ] HW test
- [ ] HW final version

### Releases
![release-v1_0-shield](https://img.shields.io/badge/release-1.0-blue.svg) | [v1.0](https://github.com/KarlVaello/Nexa-Board/releases/tag/v1.0) - Initial complete board concept

### License
- [GPL-3.0](https://github.com/KarlVaello/Nexa-Board/blob/master/LICENSE.md)
