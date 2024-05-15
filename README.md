# Processor pin descriptions as Excel worksheets

Have you ever wished processor manufacturers would issue their datasheet Pin Description tables as Excel spreadsheets? That would make it a lot easier to analyse possibilities when selecting a processor or assigning pins for a new project! 
Well, I wanted this enough to do it myself. 

My spreadsheet(s) transcribe the Pin Description table of the datasheet and then split the elements from the Function field into separate columns for each type of pin use (GPIO, RTC_GPIO, TOUCH, SPI, HPI etc.). Excel can then be used to sort on any column or select rows (pins) at will. 

[This Github repository](https://github.com/AndySymons/Processor-datasheet-pin-descriptions-as-Excel-spreadsheets/tree/main) shares the fruits of my labours. I hope you find it useful too. 

### ESP32 Series (-D0x, -S0x, -U4x) pin descriptions from datasheet
This spreadsheet is transcribed from Espressif Systems "ESP32 Series Datasheet" version 4.5 (2024), which covers:  
- ESP32-D0WD-V3
- ESP32-D0WDR2-V3
- ESP32-U4WDH
- ESP32-S0WD
- ESP32-D0WD
- ESP32-D0WDQ6
- ESP32-D0WDQ6-V3  

### ESP32-S2 pin descriptions from datasheet
This spreadsheet is transcribed from Espressif Systems "ESP32-S2 Series Datasheet" version 1.6 (2024), which covers:
- ESP32-S2
- ESP32-S2FH2
- ESP32-S2FH4
- ESP32-S2FN4R2
- ESP32-S2R2

### ESP32-WROOM-32, -32D, and -32U pin descriptions from datasheet
This spreadsheet is transcribed from Espressif Systems' "ESP32-WROOM-32 Datasheet" version 3.3 (2022) and "ESP32­WROOM-­32D & ESP32-­WROOM­-32U Datasheet" version 2.4 (2023), which are exactly the same in respect of pinout. It covers:
- ESP32-WROOM-32
- ESP32­WROOM-­32D
- ESP32-­WROOM­-32U

