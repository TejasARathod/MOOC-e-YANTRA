
# e-Yantra MOOC [Crash Course on Embedded System and Robotics] by IIT Mumbai

This course was designed to give a pragmatic approach to solve Embedded Systems and Robotics related problems. To learn how to apply these principles to solve real-world problems.
This 40 Days Course is offered along with a Challenge activity to help hone our acquired skills. It is a project based learning course which is simulation based with a debugger.
## Table of Contents
- Program Layout and Details
- Deployement
- Tech Stack
- Authors
- License
## Program Layout and Details

- Week 1 (IO interfacing):
    - Getting familiar with Microchip Studio/VSCode
    - Program and debug C code snippets.
    - Understand the function of I/O ports and the associated registers.
    - Interface I/O peripherals like Switch, Buzzer, Bar graph LEDs and LCD.
    - Understand various LCD commands and ASCII encoding.
    - Display text at different positions on the LCD and implementing a simple scrolling display.

- Week 2 (Working with sensors):
    - Interface Sharp sensors and Proximity sensor and understand ADC (Analog to Digital conversion) on Firebird V.
    - Interrupt and Position encoder for traversal of Firebird V.

- Week 3 (Motor Interfacing):
    - Direction control of DC motors present on Firebird V Robot.
    - Understanding TIMERs and associated registers in ATmega2560 for configuring TIMERs in Firebird V Robot.
    - Interrupt and Position encoder for traversal of Firebird V Robot.

- Week 4 (Challenge Activity):
    - Part1 : Time based Problem Statement (MCQ's)
    - Part2 : 
        - Challenge Activity 1: Custom character display on the LCD. 
        - Challenge Activity 2: Display waveforms from function generator on GLCD with switches representing Digital Oscilloscope (DSO).

## Deployment 

- **Step 1:** Start Microchip Studio
- **Step 2:** Build the project using the shortcut key Ctrl+Alt+F7 or from the Menu bar: Build > Rebuild solution.
- **Step 3:** Make sure you select Change Device option in Project settings and choose ATmega328P
- **Step 4:** If there are no errors present in the program, the project will get compiled correctly and you will get the message in the Output window as below. Also, Debug folder will be generated in project directory that will contain Experiment-'name'.hex file along with other build files.

**======== Rebuild All: 1 succeeded, 0 failed, 0 skipped ========**

- **Step 5:** Load the hex file on the Firebird V robot or simulator circuit once the program gets build successfully. 

## Tech Stack

**Language Used:** C

**IDE Used:** Microchip Studio


## Authors

- [@tejasrathod](https://www.linkedin.com/in/tejas-rathod-923187189/)



## License

[MIT](https://github.com/TejasARathod/MOOC-e-YANTRA/blob/c3e43447f98f89a81ce485348c0bc446a4505a8b/LICENSE)

