
## Week-2, Experiment-1 ADC Interfacing
## Table of Contents
- Aim
- Connections
- Output

## AIM
In this experiment, we had to interface ADC with the micro-controller. The aim of this experiment is to get ourselves familiar with ADC present on Firebird V robot.

ATmega2560 features a 10-bit successive approximation ADC. This built-in ADC is connected to an 16 channel Analog Multiplexer which allows 16 single ended voltage inputs constructed from the pins of Port K and Port F of ATmega2560.

In this experiment, we had to interface the White Line and IR Proximity sensors already connected on Firebird V robot. The aim of this experiment is to get ourselves familiar with the configuring and interfacing of these sensors and using the built-in ADC of ATmega2560.

Our task was to get the 8-bit ADC result from the three white line sensors and 3rd, 4th and 5th IR proximity sensors in Single Conversion Mode and display the ADC converted digital values on LCD and send the ADC data of Center White Line sensor on UART Serial Terminal.
## Connections


           Sensor	            Firebird V Interfacing	    SimulIDE Interfacing
    Left White Line Sensor   |	 PF3 [ ADC Channel 3 ]    |	PC1 [ ADC Channel 1 ]
    Center White Line Sensor |	 PF2 [ ADC Channel 2 ]    |	PC0 [ ADC Channel 0 ]
    Right White Line Sensor  |	 PF1 [ ADC Channel 1 ]    |	PC2 [ ADC Channel 2 ]
    3rd IR Proximity Sensor  |	 PF6 [ ADC Channel 6 ]    |	PC3 [ ADC Channel 3 ]
    4th IR Proximity Sensor  |	 PF7 [ ADC Channel 7 ]    |	PC4 [ ADC Channel 4 ]
    5th IR Proximity Sensor  |	 PK0 [ ADC Channel 8 ]    |	PC5 [ ADC Channel 5 ]







## Output

![](https://github.com/TejasARathod/MOOC-e-YANTRA/blob/ce2bb022a1acc2593629357d16aaaf2021cd47ea/Week2/Exp1/Screenshot%202022-06-03%20201342.png)



