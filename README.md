# 10inch-Rack-SDR-Station
10inch 4U Reck SDR Station with built in nanoVNA, Red Pitaya, 2x RTL-SDR and an HackRF

inspired from Jeff Geerlings mini-rack (https://github.com/geerlingguy/mini-rack and https://mini-rack.jeffgeerling.com) 
i set out to develop one of my own. I had a lot of parts lying around including, two Rasperry Pi's, a spare nanoVNA, 
a Red Pitaya, two RTL-SDR and an HackRF and some other parts...
The goal was to create a self contained SDR-Station, which i can take wherever i need it without the nessesaty 
for extrenal devices like monitor or keybord/mouse etc. Everything is mounted on the small 4U DeskPi RackMate T0
Onyl connection needed is Power and maybe a network cable it you need internet.
The heart will be a Raspberry Pi5 and an other Raspberry Pi4, On the Pi im running RasbianOS form an NVMe drive 
and on the Pi4 im using dragonOS. For remote conneciton the Pi4 is connetetd to a JetKVM and for the PI4 im using 
simply Raspberry Pi Connect. Apart from that of course you can still use VNC or ssh into the machines.

As for the Brackets i used JaredC01's LabStack (https://github.com/JaredC01/LabStack) as a starting point and made a few 
Modules my self in Fusion 360


List of parts included in theis build: (links are for referncece only, not affiliated or anything)

+ 1x Raspberry Pi4
+ 1x Power Over Ethernet PoE HAT für Raspberry Pi 4 B (https://www.amazon.de/dp/B0928ZD7QQ)
+ 1x Raspberry Pi5
+ 1x Waveshare PCIe to M.2 Adapter with PoE Function HAT+ (https://www.amazon.de/dp/B0DNLSZ3LF)
+ 1x JetKVM
+ 1x JetKVM
+ 2x RTL-SDR (a V3 and a V4)
+ 1x HackRF
+ 1x Red Pitaya
+ 1x GeeekPi DeskPi RackMate T0 (https://www.amazon.de/dp/B0DPGZPTPP) Brackets from here (https://makerworld.com/de/models/1027857#profileId-1010363)
+ 1x 10 Port 2.5Gb PoE Switch (https://www.amazon.de/dp/B0DDB3LHPX)
+ 1x ProtoArc XK01 TP Bluetooth Keyboard (https://www.amazon.de/dp/B0D7BPDLWJ)
+ 1x ELECROW 10" 1280×800 Touchscreen Monitor (https://www.amazon.de/dp/B0BHHQLKPY)
+ 2x GeeekPi 10 Zoll 0,5U Brush Cable Manager (https://www.amazon.de/dp/B0DSJFX6XV)
+ 1 pair of 20mm Drawer slides (https://www.amazon.de/dp/B0DPGZPTPP)
+ 10x deleyCO 0,5m flat CAT7 network cable (https://www.amazon.de/dp/B08SMHN5YN)
+ 2x RJ45 Keystone Koppler Module (https://www.amazon.de/dp/B0CH31YP7P)
+ 1x Micro HDMI to HDMI Stecker FPC-Flatcable 1080P 90 Grad up 0.5m (https://www.amazon.de/dp/B0CDRYSD29)
+ 1x Micro HDMI to mini HDMI Stecker FPC-Flatcable 1080P 90 Grad down 0.2m (https://www.amazon.de/dp/B01LZN83ID)
+ 1x USB 2.0 Typ-A to Micro-USB 0.2m (https://www.amazon.de/dp/B0967TZFT1)
+ couple of other USB cables as needed, between 0.3 and 0.5m

As for the brackets/modules i designed a few new ones:

+ Module 3x nanoVNA v2 Plus 4inch LCD
+ Module 1x Red Pitaya
+ Module 1x SDR 2x RTL 1x HackRF
+ Module 1x Keystron with passthrough, Keystron at the bottom
+ Keyboard handle
+ Drawer for storage including lid so nothing falls out in transport
+ Mounting Brackets for Monitor

