# Team ApolLO's CanSat PCBs
The mainboard features:
- **RP2350A** MCU 
- **W25Q128JVPIQ** flash memory
- **Waveshare 23721** for GPS signal
- **RFM98W 433MHz** LoRa module
- **MPU-6050** gyroscope and accelerometer
- **BMP 280** barometer and thermometer
- **USB-C connector**
- **BOOTSEL** and **RESET** buttons
- Status **LED**
- **Buzzer** for easier recovery
\
![PCB Assembled Front](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/photos/PCBAF.jpg)
![PCB Assembled Back](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/photos/PCBAB.jpg)
![PCB Front](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/photos/PCBF.jpeg)
![PCB Back](https://raw.githubusercontent.com/ApolLO-CanSat/PCB/refs/heads/main/photos/PCBB.jpeg)
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
|Id|Designator|Footprint|Quantity|Designation|
|-|-|-|-|-|
|1|R5,R24,R12,R1,R21,R23,R22|R_0805_2012Metric|7|10K|
|2|R26,R25|R_0402_1005Metric|2|4.7K|
|3|C25|C_0805_2012Metric|1|10nF|
|4|R4,R3|R_0805_2012Metric|2|27|
|5|J8|PinHeader_1x02_P2.00mm_Vertical|1|Conn_01x02_Pin|
|6|L1|AOTAB201610S3R3101T|1|3.3u|
|7|D2|LED_0402_1005Metric|1|RED|
|8|U5|RP2350-QFN-60-1EP_7x7_P0.4mm_EP3.4x3.4mm_ThermalVias|1|RP2350_60QFN|
|9|C16,C9,C8,C11|C_0402_1005Metric|4|4.7uF|
|10|C20,C3,C4,C10,C22,C12,C7,C1,C5,C6,C2|C_0402_1005Metric|11|100nF|
|11|C24,C23|C_0402_1005Metric|2|15pF|
|12|C30,C15,C17,C32,C27,C28,C19|C_0805_2012Metric|7|100nF|
|13|BZ1|CMT-4023S|1|Buzzer|
|14|J1|USB_C_Receptacle_Amphenol_12401610E4-2A|1|USB_C_Receptacle|
|15|C31|C_0805_2012Metric|1|22u|
|16|SW2,SW1,SW3|SW_Push_1P1T_NO_Vertical_Wuerth_434133025816|3|SW_Push|
|17|IC1|SON127P600X500X80-9N-D|1|W25Q128JVPIQ|
|18|C21,C13|C_0805_2012Metric|2|1uF|
|19|D1|MMBT2907AM3T5G|1|ESD7L5.0DT5G|
|20|D4,D3|D_SOD-123|2|MBR0530T1G|
|21|R11,R10|R_0805_2012Metric|2|5.1K|
|22|J10|PinHeader_1x04_P2.00mm_Vertical|1|Conn_01x04_Pin|
|23|R18|R_0805_2012Metric|1|100|
|24|J2|SMA_Amphenol_901-144_Vertical|1|Conn_Coaxial|
|25|R17|R_0402_1005Metric|1|10K|
|26|R20|R_0402_1005Metric|1|33|
|27|U3|PinHeader_1x05_P1.00mm_Vertical|1|Waveshare23721|
|28|C18|C_0805_2012Metric|1|2.2nF|
|29|U8|Bosch_LGA-8_2x2.5mm_P0.65mm_ClockwisePinNumbering|1|BMP280|
|30|R2,R14,R13|R_0805_2012Metric|3|1K|
|31|Y1|ABM8272T3|1|ABM8272T3|
|32|C29|C_0805_2012Metric|1|2.2uF|
|33|Q1|SOT-23|1|BSS138|
|34|U9|PSON50P200X300X50-9N|1|APS6404L-3SQR-ZR|
|35|J6|PinHeader_2x03_P1.00mm_Vertical|1|Conn_01x06_Pin|
|36|R15|R_0805_2012Metric|1|220|
|37|J7|JST_SH_BM03B-SRSS-TB_1x03-1MP_P1.00mm_Vertical|1|Conn_01x03_Pin|
|38|R16|R_0805_2012Metric|1|DNC|
|39|J5|JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical|1|Screw_Terminal_01x02|
|40|J9|JST_SH_BM03B-SRSS-TB_1x03-1MP_P1.00mm_Vertical|1|Conn_01x02_Pin|
|41|J11|JST_PH_B3B-PH-K_1x03_P2.00mm_Vertical|1|Conn_01x03_Socket|
|42|J3|JST_SH_BM06B-SRSS-TB_1x06-1MP_P1.00mm_Vertical|1|Conn_01x06_Socket|
|43|U4|HOPERF_RFM9XW_SMD|1|RFM98W-433S2|
|44|C14|C_0805_2012Metric|1|DNP|
|45|U1|InvenSense_QFN-24_4x4mm_P0.5mm|1|MPU-6050|
|46|J4|JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical|1|Conn_01x02_Pin|
|47|R19|R_0402_1005Metric|1|1K|

