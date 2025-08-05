# Sodimm-force rev0 <img src="https://img.shields.io/badge/KiCAD-8?logo=kicad&color=%23FF8C00" alt="KiCAD"/>
> [!IMPORTANT]
> Project wasn't produced and tested yet.
### This project is an implementation of Orange Pi Zero 2W in sodimm form-factor
![alt text](image.png)
<table style="width: 100%; table-layout: fixed;">
  <tr>
    <td rowspan="4">
      <img src="image-2.png" width="360" height="200"/>
    </td>  
    <td rowspan="4">
      <img src="image-1.png" width="400" height="200"/>
    </td>  
  </tr>
</table>

## 🎲Revisions and logs:
<table>
  <tr>
    <td>
      <strong>Revision 0</strong>
    </td>   
    <td>
      <strong>10 March 2025</strong>
    </td> 
    <td>
      CPU H616, DDR MT53E1G32D2FW-046
    </td>
    <td>
      <strong>[x] not produced</strong>
    </td>
  </tr>
</table>

## 🔧 Key Components

| Component         | Model / Type                                | Features |
|-------------------|---------------------------------------------|----------|
| **Processor**     | Allwinner H616                               | Quad-core ARM Cortex-A53 (64-bit), up to 1.8 GHz, Mali-G31 MP2 GPU (4K@60fps video decode) |
| **RAM**           | Micron MT53E1G32D2FW                         | LPDDR4 4 GB, 4266 Mbps, industrial temp range (–40°C to +105°C), dual-die package |
| **Form Factor**   | SODIMM 200-pin                               | Compact, modular design, easy integration and replacement |
| **EEPROM**        | ST M24M02                                    | 2 Mbit, I²C interface, write protection, stores calibration and settings |
| **microSD Slot**  | —                                            | Supports up to 32+ GB, for OS boot, data storage, and logs |
| **Display**       | 0.96" IPS (ST7735)                           | 160×80 resolution, SPI interface, full-color, wide viewing angles |
| **Buttons**       | 4× Tactile (KMR221GLFS)                      | For navigation and control in built-in menu system |
| **Power Supply**  | SY8843QWC (DC-DC), SPX3819 (LDO)             | High-efficiency DC-DC + low-noise LDO for stable analog power |
| **Interfaces**    | microHDMI, 2× USB Type-C                     | HDMI 2.0 (4K output), USB 2.0 OTG, ESD protection |

