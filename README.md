# openMANET

Open source mobile ad hoc network radio using mostly commodity hardware and 3d printed parts.

## Design specs
  
- Raspberry pi 5 
  - has PCIe port
  - Raspbian or OpenWRT?
- 4x sma
  - All for wifi6 antennas
  - Metallic case may require additional antenna(s) for Pi onboard BLE/wifi 
- Weatherproof 
  - No IP target for prototype, ideally IP67 for finished product
- Aux dc power 
  - For vehicle or embedded install
- PCIe radios 
  - Target 30 dbm (max for band), availability may be an issue
  - What Rpi PCIe hat?
- External batteries 
  - target for run time per battery? Step 1 may be getting nominal power draw of all this hardware. Then see what we can find to support that off the shelf
  - Prc 152? Baofeng?
- Controls 
  - Power on/off switch
  - Rotary encoder
  - radio or channel selection, etc
- Exposed ports 
  - Usb
  - Audio (3.5? Kenwood plug?)
  - Primary interface between radio and EUD (RJ45?)
  - DC power input (see above) 
  - What else?
- Do we want to target the form factor of any other radio? Would solve the “how do we carry this?” question, just use existing pouches

## Hardware List
