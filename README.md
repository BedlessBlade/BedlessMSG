# BedlessMSG
A LoRa device built from the esp8266 designed for off-grid messaging with a display, keyboard, battery, and a RFM95/RFM95W LoRa tranceiver


CRUCIAL INFORMATION:
The microstrip for the LoRa antenna is currently made for JLCPCB 1mm boards. I cannot gaurantee the functionality of the device or range tests on any other pcb manufacturer.


Development Status:
Pre-Alpha

Development stages: Pre-Alpha --> Alpha --> Beta --> Release 1.0 --> TBD


I will be trying my best to push frequent updates.

Current state: Designing boards

Pre-Alpha/Alpha roadmap: Designing boards --> Order boards --> Starting basic feature programming --> Receive boards --> Solder boards --> Finish basic firmware --> Create a development board

Current state of board design: Complete (features left: None (spi display replaced with i2c ssd1306))
Current state of basic feature programming: Just started

Board photos:
![image](https://github.com/BedlessBlade/BedlessMSG/assets/71991602/276aa1a7-efaa-4d1b-ae5c-9d6fcf4c3274)
![image](https://github.com/BedlessBlade/BedlessMSG/assets/71991602/a83e57b3-5d67-4a06-9c06-ffafa56d16b4)
![image](https://github.com/BedlessBlade/BedlessMSG/assets/71991602/dc64bfee-8421-4453-9c38-566e7c7aa546)
![image](https://github.com/BedlessBlade/BedlessMSG/assets/71991602/b2e87a25-e240-452f-94b8-b5b5bbd507ff)


BoM: so far
Wemos D1 Mini V4.0 (it has a flat side for easy mounting unlike the normal D1 Mini),
RFM95/RFM95W,
0.96 in. OLED I2C SSD1306 (im using white instead of blue),
EG1247 Switch (power switch for the pcb),
TP4056 USB-C module (just look it up you will find it),
‎150060BS75000‎ Blue LED (power LED),
‎PPTC041LFBN-RC‎ 4-pin female header,
GRM155R61H104ME14J capacitor (x3) (for de-coupling),
ERJ-3BQJ6R8V SMD Resistor (for the LED),
CONSMA020.042-G (50 ohm sma connector for 1mm pcbs),
2-pin jst connector SMD (x2) (battery and external power input, other than usb c) (can be excluded)
