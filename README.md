# Table of contents
1. [What that ?!](#1)
2. [Schematic](#2)
3. [SCSI Terminator PCB](#3)
4. [BOM](#4)

# What that ?! <a name="1"></a>
This active terminator can be use to obtain a proper terminaison whatever the length of the SCSI bus.
It must be connected after the last device in the chain.

The project has been designed with Kicad under Linux Mint.

# Schematic <a name="2"></a>
The schematic of the SCSI terminator is based on the original active version from Commodore

![Schematics](https://github.com/nobodyisinocent/SCSI-Active-terminator/assets/80821708/0be7c675-997c-438d-95cc-4144b695d717)

# SCSI Terminator PCB <a name="3"></a>

![PCB-UP](https://github.com/nobodyisinocent/SCSI-Active-terminator/assets/80821708/6df79685-b47a-4336-854d-dd28d023102e)
![PCB-DOWN](https://github.com/nobodyisinocent/SCSI-Active-terminator/assets/80821708/4a19606b-cb6c-4659-bd0b-f995d97ef486)

Final version of the pcb.

# BOM <a name="4"></a>

|Id	|Designator	|Package	|Quantity	|Value	|Reichelt part number	|Link  |
|---|---|---|---|---|---|---|
|1	|C1,C3,C5  |	SMD 1206	|3	|100nF|WAL 1206B104K500|https://www.reichelt.com/fr/en/Shopping-basket/5/index.html?ACTION=5&LA=3&nbc=1|
|2	|C2,C4,C6  |	SMD ELKO |3	|4.7µF|HA-V 4,7U 25|https://www.reichelt.com/fr/en/smd-e-cap-radial-4-7-f-25-v-105-c-1000-h-20--ha-v-4-7u-25-p228530.html?&trstct=pol_10&nbc=1|
|3	|D1        |3.0mm round type|1|-|LED 3MM RT|https://www.reichelt.com/fr/en/del-3-mm-plomb-e-rouge-191-mcd-50--led-3mm-rt-p10228.html?&trstct=pos_1&nbc=1|
|4	|R1	      | SMD1260	|1	|680R|RND 1206 1 680|https://www.reichelt.com/fr/en/r-sistance-smd-r-sistance-couche-paisse-680-o-1-1206-rnd-1206-1-680-p183362.html?&trstct=pos_0&nbc=1|
|5	|U1,U2	    |SOIC-16W	|2	|DS2107S|-|https://www.utsource.net/itm/p/11743518.html|
|6	|J1        |IDC 50 pins right angled male connector|1	|-|WSL 50W|https://www.reichelt.com/fr/en/box-connector-50-pin-angled-wsl-50w-p22839.html?&trstct=pol_5&nbc=1|

