![Github Nixie Pendant Logo(1)](https://github.com/user-attachments/assets/1f107c65-62ae-43fd-a9b0-63bc3d3a85bb)

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
- `socket/` - My bootleg IN-16 socket, very simple. just pads and holes. but like, this should hold the tube in (probably)
- `PendantLib.pretty/` - Shared part footprints
