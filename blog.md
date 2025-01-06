> [!CAUTION]
> This project contains high voltage electronics, It could concevably kill you and it will hurt.
> Don't leave children unnatended and exercise caution

# Project overview
So, I wanted to put a working nixie tube around my neck.

# Initial plans
I wanted to use a IN-16 tube, as I didn't want it to get dwarfed by the electronics, and wanted it to all fit underneath it.
I've also ended up with quite a few different PCB's in the stack because of the incredibly small surface area.

## Key voltages and voltage information
The low voltage rails will predominantly be 3.3, this voltage powers the control circuitry and is passed to the high voltage generation circuitry. It is designed this way, to minimise the additional components, caused by having to further regulate it down for the controller. The High voltage is supposed to be 170v

Other voltages that are present are:
- 5v on the BMS
- 3.7v on the BMS

## Planned Electrical Stackup
In order of closest to the tube
1. Socket PCB
2. Control PCB
3. High Voltage Gen PCB
4. BMS/Low Voltage PCB
5. Programming/Charging PCB
6. Lipo Battery

# Designing the PCBs
## BMS PCB
### The requirements
1. Handle battery charging
2. Handle safe discharge
3. Handle voltage switchover
4. Handle power regulation to 3.3v from either 5v or 3.7v
5. Contain connection points for a power switch

### Rev 1
This revision was my first proper attempt. While I managed to get it within the limited space and only on 1 side (reducing fab costs). I forgot power regulation, switch solder points and a mounting hole in the center
{{Rev 1 Photo - Copy in BSX Mods #pcb-design}}
### Rev 2
Rev 2, This was attempt 2. I remembered the voltage regulator, however I forgot the mounting hole and the switch points. I also ended up going onto the back of the PCB
{{Rev 2 Photos - Copy in Alex's DMs}}
### Rev 3
Attempt 3... Attempt 3! This revision finally adds a 1.5mm mounting hole and the points for the switch (although this is getting tight!)