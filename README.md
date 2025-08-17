UPS notes

Goals
	1. Present HID Power to Win/Linux/MacOs over USB
	2. Plug into COTS RS485/Bluetooth interfaces for BMS/UPS Inverters
	3. Plug into battery through ADC for systems without RS485
		3a. Provide battery type profiles for easy adaption to HIDPower spec
	4. Monitor line voltage to relay to host OS

Secondary
	5. Host NUT and WOLNUT server on device

How it started 
This started when my cyber power with Lead batteries died. The only LiFePo4 UPS on the market did have any communications and I wanted more run time on a budget. Combined with my interest in DIY battery packs and off grid power I thought I would build my own. There are dozens of examples for building batteries and even enough cheap LifePo4 batteries that getting more run time seemed possible. Then I realized a design for DIY UPS that would plug into my server and present itself as UPS did not exist. 

Research and inspiration
Abratchik has done much of the heaving lifting with HIDPowerDevice which presents and Arduino as a USB UPS.  PylonTech has done the other side, connecting an Arduino to a battery system and displaying vitals on a screen. 

How to reach the goals
I programmed Motorola microprocessors in the late 90s in electronics school but my career took me away from that. I hope I still have enough of it to combine the work from Abratchik and PylonTech into a system that can be plugged into any battery system and displayed as a UPS to a desktop OS.

Past hero’s work to build from:

https://github.com/abratchik/HIDPowerDevice
https://github.com/SteveintheIoW/T-Display-S3-JK-BMS-BLE-to-Solis-CAN-Pylontech/tree/main
https://github.com/networkupstools/nut
https://github.com/ludoux/esp32-nut-server-usbhid
