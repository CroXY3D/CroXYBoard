# CroXYBoard
CroXYBoard is a small 36x34mm toolboard for simplifying 3D printer tool wiring.  It is used on the CroXY and MicroXY printers.

![IRL](https://github.com/CroXY3D/CroXYBoard/blob/main/images/irl.jpg?raw=true)
![front](https://github.com/CroXY3D/CroXYBoard/blob/main/images/front_sm.png?raw=true)
![back](https://github.com/CroXY3D/CroXYBoard/blob/main/images/back_sm.png?raw=true)

This toolboard uses a 16 pin Microfit 3.0 connector and provides XH connections at the toolhead for:
* Extruder
* Hot End (Microfit 3.0 or XH)
* Thermistor
* Hot End Fan (12/24V selectable)
* Part Cooling Fan x2 (12/24V selectable)
* Switch - for endstop or other use
* Aux - 3 more connections for BLTouch or other use
* LED - Always on (12/24V selectable via trace cut/jump).  This may be used as a generic power source.

It is possible to use 2 CroXYBoards with one near the printer's controller board and the other at the toolboard.  This may simplify wiring somewhat.  

# BOM  
* 1x PCB (See Below)
* 1x 16 pin Microfit3 board connector.  [Right angle Molex 43045-1600](https://www.digikey.com/en/products/detail/molex/0430451600/531424) or [Upright Molex 43045-1612](https://www.digikey.com/en/products/detail/molex/0430451612/531412).
* 1x [2 pin Microfit3 upright board connector - Molex 43650-0227](https://www.digikey.com/en/products/detail/molex/0436500227/3310541?s=N4IgTCBcDaICwGYBsBWADAWjWMB2EAugL5A)
* 2x [4 pin XH connectors - JST B4B-XH-A](https://www.digikey.com/en/products/detail/jst-sales-america-inc/B4B-XH-A-LF-SN/1651047)
* 5x [2 pin XH connectors - JST B2B-XH-A](https://www.digikey.com/en/products/detail/jst-sales-america-inc/B2B-XH-A-LF-SN/1651045)
* 2x [3 pin jumper headers - Molex 22032031](https://www.digikey.com/en/products/detail/molex/0022285034/6167122) (optional, may solder jumper instead)
* 2x [2 pin jumpers AMP 861410021H11LF](https://www.digikey.com/en/products/detail/amphenol-icc-fci/861410021H11LF/4417821) (optional, may solder jumper instead)
* 1x 16 pin [Microfit3 receptacle - Molex 43025-1600](https://www.digikey.com/en/products/detail/molex/0430251600/531406), or [prewired 16 pin microfit cable harness](https://www.aliexpress.com/item/4001132970645.html?spm=a2g0s.9042311.0.0.27424c4d12p2WJ) (recommended)

# PCB Manufacturing
I recommend [JLCPB](http://https://jlcpcb.com/) for getting the boards made inexpensively and efficiently.
[OshPark](https://oshpark.com/) is another option.
You only need to upload the gerbers zip file.



# DISCORD
We now have a [Discord](https://discord.gg/ryj6wyx) to discuss CroXYBoard and CroXY!  
  


