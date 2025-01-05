![Plain Nixie Pendant Logo](https://github.com/user-attachments/assets/538091d9-3856-4dc7-a6c1-e9d71c625f2d)

A DIY, wearable pendant made from an IN-16 and quite a few boards

> [!CAUTION]
> This project contains high voltage electronics, It could concevably kill you and it will hurt.
> Don't leave children unnatended and exercise caution

## Key Voltages
LV: 3.3v, HV: 170v

## Planned electrical stackup
This is in order of closest to tube
1. Socket PCB
2. Control PCB
3. High Voltage Generation PCB
4. BMS board
5. Programming/Charging board
6. Battery


## Folder Layout
- `bms/` - Board files for the BMS (Battery Management System), handles lipo charging and safe discharge, usb & battery cutover and power regulation to the LV rail
