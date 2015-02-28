# ePaperFrame

Trying to get this running:
- Hook up a Spark Core to a Seeedstudio ePaper panel
- Push data to Spark or make Spark pull data from e.g. dropbox to be displayed 

I connected the Seeedstudio ePaper shield and the panel to the Spark Core like this:

| ePaper shield (Seeedstudio) | Spark Core | ePaper panel
|----------|--------|------
| D2 | D2 |	M_EPD_PANEL_ON 
| D3 | D3 | M_EPD_BORDER 
| D4 | A2 | M_/SD_CS 
| D5 | A7 | M_EPD_PWM 
| D6 | D6 | M_EPD_/RESET 
| D7 | D7 | M_EPD_BUSY 
| D8 | D4 | M_EPD_DISCHARGE
| D9 | n/a | M_/WORD_STOCK_CS
| D10 | D0 | M_/EPD_CS
| A0 | A0 | M_TEMP_SEN
| A1 | D5 | M_OE123
| A2 | n/a | M_CKV
| A3 | A6 | M_STV_IN
| M_MOSI | A5 | n/a
| M_SCK/CLK | A3 | n/a
| M_MISO | A4 | n/a
| GND | GND | n/a
| 3.3V | ext. 3.3V | M_VCC_3V3
| 5V | ext. 5V | M_VCC_5V



Still pretty busy with understanding the whole matter. Any kind of help very much appreciated at any time.
