# LBriduino
## Description
This is a PCB design for keencave's [LBridge](https://github.com/keencave/LBridge) code. It's my very first design and still in testing, dragons beware!

Made with free version of EAGLE for BM019 and RFDuino.

The switch has the states On (1-2) and Off/Testing (2-3). The battery can be charged in any state, in the off-state the NFC and RFDuino modules are disconnected. But there are two testing vias that can be shorted or connected to an ampere meter.

![PCB screenshot](https://raw.githubusercontent.com/chaosbiber/LBriduino/master/pcb.png)

There's **a bug** in the current design: Between C1 and C2 a line to ground is missing.

## Parts
(product links from 2017/12/10)

* BM019  
http://www.solutions-cubed.com/bm019/  
http://www.warburtech.co.uk/products/modules/solutions.cubed.bm019.serial.to.nfc.converter/
* RFduino RFD22301  
https://www.mouser.de/ProductDetail/RF-Digital-Wireless/RFD22301/
* Lipo Charger IC MCP73831T-2ACI/OT
* C1/C2: Capacitor 0603 4.7µF (measured 3.8µF)
* C3: Capacitor 0603 100nF (to program RFDuino)
* R1: 330 Ohm
* R2: 3kOhm (for ~333mA charging speed, default 2kOhm for ~500mA. Ic = 1000/R2)
* red LED 0603
* Sliding switch SPDT (generic, I ordered Apem MHSS1105)
* Molex 105017-0001 USB micro-B connector
* USB programmer for the RFDuino (RFD22121), or any adapter with serial connection at 3.3V level