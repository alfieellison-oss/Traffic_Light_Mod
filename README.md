# Traffic_Light_Mod
This is the repo for a microcontroller module that im making, designed to work with an ESP32 microcontroller but will hopefully be compatible with others.

<img width="679" height="515" alt="image" src="https://github.com/user-attachments/assets/63728eba-b17f-44dc-bb25-b7d909d9bab4" />


## Features

- 5 LED's'

- 3 resistors
 
- A right angled 4 pin connector

## PCB

Here are pictures of my pcb:

| \*\*Schematic\*\* | \*\*PCB\*\* |

|---------------|---------|
=======
<img width="202" height="448" alt="image" src="https://github.com/user-attachments/assets/32a76acb-e50f-4377-a24c-7a74fe26f590" />
<img width="202" height="448" alt="image" src="https://github.com/user-attachments/assets/f0186697-f361-427e-bd38-fc44258dfa60" />

## Case
 To lenghten the life of the module i decided to add a case to it that should help prevent the solder jpints from cracing due to acidental bending.
 
 <img width="550" height="420" alt="image" src="https://github.com/user-attachments/assets/8f504a72-6fa9-4169-a162-55502e157e83" />



##BOM
| Id | Reference  | Component      | Footprint                                        | Quantity | RS Stock No | Title                                                                                    | Manufacturer Part No | Unit Price |
| -- | ---------- | -------------- | ------------------------------------------------ | -------- | ----------- | ---------------------------------------------------------------------------------------- | -------------------- | ---------- |
| 1  | D1         | LED Red        | LED_D5.0mm_Clear                                 | 1        | 2285972     | Kingbright 2 V Red LED 5mm Through Hole                                                  | L-53ID               | 0.17       |
| 2  | D2         | LED Yellow     | LED_D5.0mm_Clear                                 | 1        | 2471684     | Kingbright 2.5 V Yellow LED 5mm Through Hole                                             | L-53SYD              | 0.312      |
| 3  | D3         | LED Green      | LED_D5.0mm_Clear                                 | 1        | 2286004     | Kingbright 2 V Green LED 5mm Through Hole                                                | L-53GD               | 0.17       |
| 4  | R1, R2, R3 | 150Ω Resistor  | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | 3        | 7077603     | RS PRO 150Ω Carbon Film Resistor 0.25W ±5%                                               |                      | 0.145      |
| 5  | J1         | Conn_01x04_Pin | PinHeader_1x04_P1.27mm_Horizontal                | 1        | 1982926     | Samtec TMS Series Right Angle Pin Header, 4 Contact(s), 1.27 mm Pitch, 1 Row, Unshrouded | TMS-104-01-G-S-RA    | 0.78       |
