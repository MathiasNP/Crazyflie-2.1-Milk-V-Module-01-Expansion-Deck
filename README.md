# Crazyflie 2.1 Milk-V Duo Module 01 Expansion Deck
This project designs a PCB expansion deck for Bitcraze Crazyflie 2.1 including a dual-core GHz CPU with additional interfaces for communication

---
## CAD program
- **KiCad 9.0** 

## Key components
- **Milk-V Duo Module 01** 
- **SD card connector:** 32GB minimum
- **USB connector pads** 
- **Expansion connectors to Crazyflie** 
- **DC-DC converter for 3.3V**

### For testing
- **Crazyflie 2.1** with Crazyradio USB Dongle
- **Linux computer** 
	- With Docker installed
	- Preferably Linux Mint or Ubuntu
	- Minimum 4GB RAM, 8GB recommended
- **Jumper cables:** For Crazyflie-to-MilkV connection

---
## File Reference
- **`BT-MV Duo 01 Deck/`**: Project root folder.

- **`BT-MV Duo 01 Deck.kicad_pcb`**: KiCad PCB layout file.  
- **`BT-MV Duo 01 Deck.kicad_prl`**: KiCad project local settings file.  
- **`BT-MV Duo 01 Deck.kicad_pro`**: KiCad project file.  

- **`MV Duo 01 Deck Schematics/`**: Hierarchical schematics for the deck design.  
  - **`BT-MV Duo 01 Deck.kicad_sch`**: Top-level schematic.  
  - **`BT-Power_CFexp.kicad_sch`**: Power management and Crazyflie expansion interface.  
  - **`BT-SDcard.kicad_sch`**: microSD (SD/MMC) interface.  
  - **`BT-USB_UART.kicad_sch`**: USB interface and UART debug port.  
  - **`BT-CameraOV.kicad_sch`**: Camera connector and related signals.  
  - **`BT-MV_DM01.kicad_sch`**: Milk-V Duo Module 01 integration (pins, power, straps).  
  - **`BT-Others.kicad_sch`**: Miscellaneous signals and support circuits.  

- **`BT-MVD01 libraries/`**: Custom KiCad libraries used by the project.  
  - **`Symbols and Footprints/`**: Symbol/footprint library folder.  
  - **`3D Models/`**: 3D models for custom footprints.  

- **`BT-Milk V Duo S.pretty/`**: KiCad footprint library (`.pretty`).  
- **`BT-MV Duo 01 Deck.csv`**: BOM / component list.  
- **`BT-MV Duo 01 Deck.kicad_dru`**: KiCad custom design rules.  

- **`Related Work/`**: Reference material from related designs.  
  - **`CF Proto Exp/`**: Crazyflie expansion/deck project and documentation.  
  - **`Milk Module schematics/`**: Schematics of the Milk-V module and EVB.  
  - **`Camera OV5674/`**: Reference material for the OV5674 camera.
