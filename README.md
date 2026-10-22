# Condor
Custom flight computer for CMRC's spaceshot

## Subsystems
<img width="450" alt="System Diagram" src="https://github.com/user-attachments/assets/37176419-8cd9-4a9e-abc9-4fa01e46f629" />

### Schematic: Current Assignments

| Subsystem | Person Assigned |
| :--- | :--- |
| **IMU 1** (BMI088 + ADXL375) | Mustafa |
| **IMU 2** (LSM6DSV320X) | Aronyak |
| **Altimeter / Barometer** (MS561101BA) | Tarun |
| **Magnetometer** (LIS3MDL) | Shaun |
| **RF** (not sure) | Florence |
| **MCU** (STM32F413RGT6) | Richard |
| **GPS** (u-blox M10. Not sure which) | Jason, Sushrut |
| **Power** | Aarna |
| **Pyro** | N/A |
| **Memory/storage?** (not sure if spec-ed) | N/A |

## Part Imports
Import all of the following: symbol, footprint, and 3D model from component sites directly or from sites like [UltraLibrarian](https://www.ultralibrarian.com/) and [SnapMagic](https://www.snapeda.com/)

Do NOT use any of the default global libraries. Local libraries for resistors and other components coming from Pelican soon(TM)

For the time being, put imported files into the pre-existing `Condor_Imported` libraries

## Misc Notes
**Avoid merge conflicts:** don't edit the same file as someone else at the same time. Libraries might be a bit cooked, but we'll see

## Tentative Pinouts
<img width="333" height="372" alt="image" src="https://github.com/user-attachments/assets/49a0c9aa-3eff-461c-ae2a-8c9dbf7ae0b5" />

## Todo
- To use or not to use hardware interrupt pins for IMUs
