# Team ApolLO's CanSat PCBs
The mainboard features:
- **RP2350A** MCU 
- **W25Q64FVSSIG** flash memory
- **Waveshare 23721** for GPS signal
- **RFM98W 433MHz** LoRa module
- **MPU-6050** gyroscope and accelerometer
- **BMP 280** barometer and thermometer
- **USB-C connector**
- **BOOTSEL** and **RESET** buttons
- Status **LED**
- **Buzzer** for easier recovery
\
![Mainboard schematic](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/schematics/CanSat.svg)
![MCU schematic](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/schematics/CanSat-RP2350A.svg)
\
[Schematics in PDF file](https://github.com/ApolLO-CanSat/PCB/blob/main/schematics/CanSat.pdf)
\
![PCB Schematic Front](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/schematics/CanSat-F_Cu.svg)
![PCB Schematic Back](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/schematics/CanSat-B_Cu.svg)
\
[PCB schematic in PDF file](https://github.com/ApolLO-CanSat/PCB/blob/main/schematics/CanSatPCB.pdf)
---
## BOM
| Reference | Qty | Value | DNP | Exclude  from  BOM | Exclude  from  Board | Footprint | Datasheet |
|-|-|-|-|-|-|-|-|
| BZ1 | 1 | Buzzer |  |  |  | Buzzer_Beeper:MagneticBuzzer_Kingstate_KCG0601 | ~ |
| C1,C2,C3,C4,C5,C6,C7,C10,C12,C27,C28,C30 | 12 | 100nF |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| C8,C9,C11,C16 | 4 | 4.7uF |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| C13,C14,C21 | 3 | 1uF |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| C15,C32 | 2 | 100n |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| C17 | 1 | 0.1uF |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| C18,C19 | 2 | 2.2nF |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| C29 | 1 | 2.2uF |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| C31 | 1 | 22u |  |  |  | Capacitor_Tantalum_SMD:CP_EIA-2012-15_AVX-P | ~ |
| D1 | 1 | ESD7L5.0DT5G |  |  |  | SamacSys_Parts:MMBT2907AM3T5G | https://www.onsemi.com/pub/Collateral/ESD7L-D.PDF |
| D2 | 1 | RED |  |  |  | LED_SMD:LED_0402_1005Metric | ~ |
| D3 | 1 | MBR0530 |  |  |  | Diode_SMD:D_SOD-123 | http://www.mccsemi.com/up_pdf/MBR0520~MBR0580(SOD123).pdf |
| IC1 | 1 | W25Q128JVPIQ |  |  |  | SamacSys_Parts:SON127P600X500X80-9N-D | https://www.winbond.com/hq/search-resource-file.jsp?partNo=W25Q128JVPIQ&type=datasheet |
| J1 | 1 | USB_C_Receptacle |  |  |  | Connector_USB:USB_C_Receptacle_Amphenol_12401610E4-2A | https://www.usb.org/sites/default/files/documents/usb_type-c.zip |
| J2 | 1 | Conn_Coaxial |  |  |  | Connector_Coaxial:SMA_Amphenol_901-144_Vertical | ~ |
| J3 | 1 | Conn_01x06_Socket |  |  |  | Connector_JST:JST_SH_BM06B-SRSS-TB_1x06-1MP_P1.00mm_Vertical | ~ |
| J4,J8,J9 | 3 | Conn_01x02_Pin |  |  |  | Connector_PinHeader_1.00mm:PinHeader_1x02_P1.00mm_Vertical | ~ |
| J5 | 1 | Screw_Terminal_01x02 |  |  |  | TerminalBlock:TerminalBlock_bornier-2_P5.08mm | ~ |
| J6 | 1 | Conn_01x06_Pin |  |  |  | Connector_PinHeader_1.00mm:PinHeader_2x03_P1.00mm_Vertical | ~ |
| J7 | 1 | Conn_01x03_Pin |  |  |  | Connector_PinHeader_1.00mm:PinHeader_1x03_P1.00mm_Vertical | ~ |
| J10 | 1 | Conn_01x04_Pin |  |  |  | Connector_PinHeader_1.00mm:PinHeader_1x04_P1.00mm_Vertical | ~ |
| L1 | 1 | 3.3u |  |  |  | Inductor_SMD:L_6.3x6.3_H3 | ~ |
| R1,R2,R12,R21,R22,R23 | 6 | 10K |  |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| R3,R4,R5,R6,R7,R8,R9 | 7 | 27 |  |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| R10,R11 | 2 | 5.1K |  |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| R13,R14 | 2 | 1K |  |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| R15 | 1 | 220 |  |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| R16 | 1 | DNC | DNP |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| R18 | 1 | 100 |  |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| R20 | 1 | 33 |  |  |  | Resistor_SMD:R_0805_2012Metric | ~ |
| SW1,SW2 | 2 | SW_Push |  |  |  | Button_Switch_SMD:SW_Push_1P1T_NO_Vertical_Wuerth_434133025816 | ~ |
| U1 | 1 | MPU-6050 |  |  |  | Sensor_Motion:InvenSense_QFN-24_4x4mm_P0.5mm | https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf |
| U3 | 1 | Waveshare23721 |  |  |  | Connector_PinHeader_1.00mm:PinHeader_1x05_P1.00mm_Vertical |  |
| U4 | 1 | RFM98W-433S2 |  |  |  | RF_Module:HOPERF_RFM9XW_THT | https://www.hoperf.com/data/upload/portal/20181127/5bfcdb5e17543.pdf |
| U5 | 1 | RP2350_60QFN |  |  |  | RP2040:RP2350-QFN-60-1EP_7x7_P0.4mm_EP3.4x3.4mm_ThermalVias |  |
| U8 | 1 | BMP280 |  |  |  | Package_LGA:Bosch_LGA-8_2x2.5mm_P0.65mm_ClockwisePinNumbering | https://ae-bst.resource.bosch.com/media/_tech/media/datasheets/BST-BMP280-DS001.pdf |
| U9 | 1 | APS6404L-3SQR-ZR |  |  |  | APS6404L-3SQR-ZR:PSON50P200X300X50-9N |  |
| Y2 | 1 | ASE-12.000MHz-E-T |  |  |  | SamacSys_Parts:ASE12000MHzET | https://abracon.com/Oscillators/ASEseries.pdf |
