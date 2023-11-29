# Table of contents
1. [What that ?!](#1)
2. [Schematic](#2)
3. [SCSI Terminator PCB](#3)
4. [BOM](#3)

# What that ?! <a name="1"></a>
This active terminator can be use to obtain a proper terminaison whatever the length of the SCSI bus.
It must be connected onto the last device in the chain.

The project has been designed with Kicad under Linux Mint.

# Schematic <a name="2"></a>
The schematic of the SCSI terminator is based on the original active version from Commodore

![Schematics](https://github.com/nobodyisinocent/SCSI-Active-terminator/assets/80821708/0be7c675-997c-438d-95cc-4144b695d717)

# SCSI Terminator PCB <a name="3"></a>

![PCB-UP](https://github.com/nobodyisinocent/SCSI-Active-terminator/assets/80821708/6df79685-b47a-4336-854d-dd28d023102e)
![PCB-DOWN](https://github.com/nobodyisinocent/SCSI-Active-terminator/assets/80821708/4a19606b-cb6c-4659-bd0b-f995d97ef486)

Final version of the pcb's adapter.

# BOM <a name="3"></a>

|Id	|Designator	|Package	|Quantity	|Designation	|Reichelt part number	|Link  |
|---|---|---|---|---|---|---|
|1	|C1,C3,C5  |	SMD 1206	|3	|UF10-005	|100nF	| |
|2	|C2,C4,C6   |	SMD Tantalum 7260	|3	|1N4150	|4.7µF	| |
|3	|D1        |LED 3.0mm	|1	|	|	| |
|4	|R1	      | SMD1260	|1	|680R	METALL | 680R	| |
|5	|U1,U2	    |SOIC-16W	|2	| | | |
|6	|J1        |SUB-D	|1	|ZIF HEADER| |  |

