# Wireless E-Stop Design

This document summarize the general design concept of the wireless emergency stop of the Universal 3-axis robotic arm with the X-Bee RF modulus.

## Getting Started

These instructions is providing the documentation, design, and instruction for setting up the X-Bee RF modulus on Arduino

### Prerequisites
#### Hardware

The hardware required for the design involves antenna, X-Bee Pro 5281, Arduino, and the Universal robotic arm control box.

Additional wiring is required for the Universal Arm Control Box. Configuration on the I/O is also required for coordinating wires

The BOM is listed as shown below:

| Name of the Components     | Quantity|
| :------------- | :------------- |
| Arduino Uno                                      | 1       |
| X-Bee Pro 5281                                  | 2       |
| X-Bee Explorer Regulated Boards      | 2       |
| X-Bee Explorer USB                            | 1       |
| Prototype board                                 | 1       |
| 24V Transistor                                     | 1       |

The Wiring is Shown as the follow:

/remote_estop wiring.jpg

#### Software

The system requires two sets of configuration. One set is done on the XCTU, the graphical interface for configuring the X-Bee modulus. And the other set is done on the universal robotic arms for I/O configuration.

The XCTU software can be downloaded here. 

[XCTU Configuration](https://www.digi.com/products/embedded-systems/digi-xbee/digi-xbee-tools/xctu)

The master code should be flashed into the Arduino. Here is a sample code for Arduino:

The X-Bee transmitter control code are presented in the following repository
