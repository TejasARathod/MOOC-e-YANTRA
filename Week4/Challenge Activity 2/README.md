
## Week-4, Challenge Activity-2 Design Digital Oscilloscope
## Table of Contents
- Aim
- Connections
- Output

## AIM
In this experiment, we had to display waveforms from Function Generator on GLCD with switches representing Digital Oscilloscope (DSO).

The GLCD or DSO screen has total size of 128 x 64 pixels, which is divided into two sections:

- DISPLAY WAVEFORM
Area where the input waveform is to be displayed (may it be Sine, Square, etc.).
The center line is a reference line about which the waveform should be symmetric.
The height of this area should accomodate the waveform with max. Vpp of 5V.
The width of this area should accomodate the waveform with:
min. frequency of 250 Hz (0.25 kHz)
max. frequency of 2000 Hz (2 kHz)
- DISPLAY WAVEFORM INFO
Area where the information about the waveform is to be displayed.
The peak-to-peak voltage (Vpp), frequency in kHz, ms/div, V/div.
## Connections

- Input channel from Function Generator:
    - Arduino Pin A0 --> Atmega2560 PORTK Pin 0 (PK0)
    - Arduino Pin Aref --> 5 V

- GLCD Connections:

        GLCD pins    |	Arduino Pins  |	Atmega2560 pins
        D0	       |         22	      |      PA0
        D1	       |         23	      |      PA1
        D2	       |         24	      |      PA2
        D3	       |         25	      |      PA3
        D4	       |         26	      |      PA4
        D5	       |         27	      |      PA5
        D6	       |         28	      |      PA6
        D7	       |         29	      |      PA7
        RS	       |         37	      |      PC0
        RW	       |         36	      |      PC1
        EN	       |         35	      |      PC2
        RST	       |         32	      |      PC5
        CS1	       |         34	      |      PC3
        CS2	       |         33	      |      PC4

Switch Connections:

        Switch Pins  |	Arduino Pins   | 	Atmega pins
        DIV+	     |       20	       |        PD1
        DIV-	     |       19	       |        PD2
        HOLD	     |       18	       |        PD3
        UP	         |       2	       |        PE4
        DOWN	     |       3	       |        PE5
## Output

![](https://github.com/TejasARathod/MOOC-e-YANTRA/blob/076a75323d59063f83865ec37055463b7371940b/Week4/Challenge%20Activity%202/Screenshot%202022-06-03%20221306.png)



