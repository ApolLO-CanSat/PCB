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
|1|R24,R12,R1,R21,R23,R22|R_0805_2012Metric|6|10K|
|2|R2,R14,R13|R_0805_2012Metric|3|1K|
|3|Q1|SOT-23|1|BSS138|
|4|D4,D3|D_SOD-123|2|MBR0530T1G|
|5|C32,C30,C28,C27,C17,C15|C_0805_2012Metric|6|100nF|
|6|C31|C_0805_2012Metric|1|22u|
|7|C29|C_0805_2012Metric|1|2.2uF|
|8|C21,C13|C_0805_2012Metric|2|1uF|
|9|C19,C18|C_0805_2012Metric|2|2.2nF|
|10|R4,R7,R3,R8,R9,R6,R5|R_0805_2012Metric|7|27|
|11|J8|PinHeader_1x02_P2.00mm_Vertical|1|Conn_01x02_Pin|
|12|L1|AOTAB201610S3R3101T|1|3.3u|
|13|D2|LED_0402_1005Metric|1|RED|
|14|U5|RP2350-QFN-60-1EP_7x7_P0.4mm_EP3.4x3.4mm_ThermalVias|1|RP2350_60QFN|
|15|C16,C9,C8,C11|C_0402_1005Metric|4|4.7uF|
|16|C20,C3,C4,C10,C22,C12,C7,C1,C5,C6,C2|C_0402_1005Metric|11|100nF|
|17|C24,C23|C_0402_1005Metric|2|15pF|
|18|BZ1|CMT-4023S|1|Buzzer|
|19|J1|USB_C_Receptacle_Amphenol_12401610E4-2A|1|USB_C_Receptacle|
|20|SW2,SW1,SW3|SW_Push_1P1T_NO_Vertical_Wuerth_434133025816|3|SW_Push|
|21|IC1|SON127P600X500X80-9N-D|1|W25Q128JVPIQ|
|22|D1|MMBT2907AM3T5G|1|ESD7L5.0DT5G|
|23|R11,R10|R_0805_2012Metric|2|5.1K|
|24|J10|PinHeader_1x04_P2.00mm_Vertical|1|Conn_01x04_Pin|
|25|R18|R_0805_2012Metric|1|100|
|26|J2|SMA_Amphenol_901-144_Vertical|1|Conn_Coaxial|
|27|R17|R_0402_1005Metric|1|10K|
|28|R20|R_0402_1005Metric|1|33|
|29|U3|PinHeader_1x05_P1.00mm_Vertical|1|Waveshare23721|
|30|U8|Bosch_LGA-8_2x2.5mm_P0.65mm_ClockwisePinNumbering|1|BMP280|
|31|Y1|ABM8272T3|1|ABM8272T3|
|32|U9|PSON50P200X300X50-9N|1|APS6404L-3SQR-ZR|
|33|J6|PinHeader_2x03_P1.00mm_Vertical|1|Conn_01x06_Pin|
|34|R15|R_0805_2012Metric|1|220|
|35|J7|JST_SH_BM03B-SRSS-TB_1x03-1MP_P1.00mm_Vertical|1|Conn_01x03_Pin|
|36|R16|R_0805_2012Metric|1|DNC|
|37|J5|JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical|1|Screw_Terminal_01x02|
|38|J9|JST_SH_BM03B-SRSS-TB_1x03-1MP_P1.00mm_Vertical|1|Conn_01x02_Pin|
|39|J11|JST_PH_B3B-PH-K_1x03_P2.00mm_Vertical|1|Conn_01x03_Socket|
|40|J3|JST_SH_BM06B-SRSS-TB_1x06-1MP_P1.00mm_Vertical|1|Conn_01x06_Socket|
|41|U4|HOPERF_RFM9XW_SMD|1|RFM98W-433S2|
|42|C14|C_0805_2012Metric|1|DNP|
|43|U1|InvenSense_QFN-24_4x4mm_P0.5mm|1|MPU-6050|
|44|J4|JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical|1|Conn_01x02_Pin|
|45|R19|R_0402_1005Metric|1|1K|


