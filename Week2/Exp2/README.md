
## Week-2: Experiment-2 ADC Interfacing with Interrupt
## Table of Contents
- Aim
- Connections
- Output

## AIM
In this experiment, we had to interface ADC with the micro-controller. The aim of this experiment is to get ourselves familiar with ADC present on Firebird V robot.

ATmega2560 features a 10-bit successive approximation ADC. This built-in ADC is connected to an 16 channel Analog Multiplexer which allows 16 single ended voltage inputs constructed from the pins of Port K and Port F of ATmega2560.

In this experiment, we had to interface the White Line and IR Proximity sensors already connected on Firebird V robot. The aim of this experiment is to get ourselves familiar with the configuring and interfacing of these sensors and using the built-in ADC of ATmega2560.

Our task was to get the 10-bit ADC result from the 2nd Sharp sensor in Single Conversion Mode using the ADC Conversion Interrupt. Display the ADC data on LCD and send the same to UART Serial Terminal.
## Connections


           Sensor	            Firebird V Interfacing	       SimulIDE Interfacing
    2nd Sharp Sensor       |	 PK2 [ ADC Channel 10 ]     |	PC0 [ ADC Channel 0 ]
    





## Output

![](https://github.com/TejasARathod/MOOC-e-YANTRA/blob/9980589886b43c6e249f13e53477e5ca42addb84/Week2/Exp2/unknown.png)



