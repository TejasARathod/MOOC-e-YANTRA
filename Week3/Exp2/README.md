
## Week-3: Experiment-2 Speed Control using 8 bit Phase Correct PWM Mode
## Table of Contents
- Aim
- Connections
- Output

## AIM
In this experiment, we had to increase and decrease the speed of motors using Phase Correct PWM Mode. The aim of this experiment is to get one familiar with one of the PWM mode available on the ATmega2560.

In this experiment, we had to interface the L293D motor driver already connected on Firebird V robot and the Timer connected to the ATmega2560.
## Connections

- Motors are connected to the Microcontroller through L293D Motor Driver IC.

   
        Motors Pin   |	Firebird V Interfacing  |	SimulIDE Interfacing
        RB	       |           PA3	            |     PC3
        RF	       |           PA2	            |     PC2
        LF	       |           PA1	            |     PC1
        LB	       |           PA0	            |     PC0

- PWM Pins of the Microcontroller are connected to the L293D Motor Driver IC.

        PWM Pin       |	 Firebird V Interfacing    |	SimulIDE Interfacing
        Left Motor	|            PL3	           |          PD5
        Right Motor	|            PL4	           |          PD6
## Output

![](https://github.com/TejasARathod/MOOC-e-YANTRA/blob/3129ef3cb7c7cd15ed4b1576727dd531158da0ad/Week3/Exp2/Screenshot%202022-06-03%20204502.png)



