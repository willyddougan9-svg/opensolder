# OpenSolder C245 Build - Sourcing Lists

## 1. DigiKey / Mouser (Critical Silicon & ICs)
Order genuine parts from authorized distributors for precision and safety.

| Reference | Value / Description | Footprint | Notes / Purpose |
| :--- | :--- | :--- | :--- |
| **U7** | STM32F072CBTx | LQFP-48 | Main microcontroller |
| **U5** | MAX4238ASA | SOIC-8 | Low-noise op-amp (thermocouple sensing) |
| **U3** | Si8751 | SOIC-8 | Isolated MOSFET gate driver |
| **U8** | PCT2075GV | TSOP-6 | I2C cold-junction temp sensor |
| **Q1, Q2** | KIA50N06BD (or equiv 50A/60V) | TO-252-2 (DPAK) | Main heater switching MOSFETs |
| **U2** | L78L24_SOT89 | SOT-89-3 | 24V linear regulator |
| **U4** | AP2111H-3.3 | SOT-223 | 3.3V LDO regulator |
| **PS1** | PDSE1-S24-S5-S | PDSE1 SIP module | Isolated 24V to 5V DC-DC converter |
| **U1** | VOS628A | SOP-4 | Optocoupler |
| **D1** | MB6S-TP | TO-269AA | SMD bridge rectifier (0.5A/600V) |
| **D2, D3** | S1M | D_SMA | 1A / 1000V general-purpose rectifiers |
| **Y1** | 8MHz Crystal | HC49-SD (SMD) | Microcontroller system clock |
| **F1** | 5x20mm Fast 12A Fuse + Holder | Schurter 0031.8201 | Main heater overcurrent protection |

---

## 2. Amazon / Budget Channels (Passives, Hardware & Interface)

| Reference | Value / Item | Package / Footprint | Qty | Notes |
| :--- | :--- | :--- | :--- | :--- |
| **U6** | SSD1306 SPI 1.54" or 0.96" OLED | 7-pin SPI module | 1 | Display screen |
| **SW2** | PEC11R-RotEnc | EC11 rotary encoder + switch | 1 | Control dial with knob |
| **C1** | 47µF Electrolytic | Radial D8.0mm, P3.50mm | 1 | 25V or 35V bulk capacitor |
| **C2, C3, C4, C6, C11** | 1µF Ceramic | 1210 Metric (50V) | 5 | SMD ceramic caps |
| **C5, C8, C12–C19** | 100nF (0.1µF) | 0805 Metric | 10 | SMD decoupling caps |
| **C7, C20, C21** | 10nF (0.01µF) | 0805 Metric | 3 | SMD filter caps |
| **C9, C10** | 20pF | 0805 Metric | 2 | Crystal load caps |
| **R1–R5, R9, R11, R13, R15, R17** | 10kΩ | 0805 Metric | 9 | Pull-ups / dividers |
| **R10, R12, R14, R16, R18** | 100kΩ | 0805 Metric | 5 | Sensor / bias resistors |
| **R19, R20** | 3.3kΩ | 0805 Metric | 2 | I2C pull-ups |
| **R6** | 22kΩ | 0805 Metric | 1 | Divider resistor |
| **R7** | 100Ω | 0805 Metric | 1 | Gate/signal resistor |
| **R8** | 390Ω | 0805 Metric | 1 | Indicator resistor |
| **J1** | 3-Pin 5.00mm Terminal Block | Phoenix MSTBVA 1x03 vertical | 1 | Power input connector |
| **J2** | Hirose RPC1-12RB-6P (or GX12-5/6) | Panel mount socket | 1 | Iron handle connector |
| **J3–J5** | 2.54mm Pin Headers | Breakaway male/female | Strips | SWD / UART / Reset |
