# LBriduino
## Description
This is a PCB design for keencave's [LBridge](https://github.com/keencave/LBridge) code. It's my very first design and still in testing, dragons beware!

Made with free version of EAGLE for BM019 and RFDuino.

![PCB screenshot](https://raw.githubusercontent.com/chaosbiber/LBriduino/master/pcb.png)

## Parts
(product links from 2017/12/10)

* BM019  
http://www.solutions-cubed.com/bm019/  
http://www.warburtech.co.uk/products/modules/solutions.cubed.bm019.serial.to.nfc.converter/
* RFduino RFD22301  
[mouser.de](https://www.mouser.de/ProductDetail/RF-Digital-Wireless/RFD22301/?qs=sGAEpiMZZMsrChSOYEGTCT%252bqHrbsfX8g2IB00KAX%252brY%3d)
* Lipo Charger IC MCP73831T-2ACI/OT
* C1/C2: Capacitor 0603 4.7µF (measured 3.8µF)
* R1: 330 Ohm
* R2: 3kOhm (for ~333mA charging speed, default 2kOhm for ~500mA. Ic = 1000/R2)
* red LED 0603
* Sliding switch SPDT
* USB programmer for the RFDuino (RFD22121), or any adapter with serial connection at 3.3V level