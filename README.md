AVR Refrigerator Controller (AVR Assembly)
Project Description

This repository contains a Refrigerator Control System implemented using AVR Assembly.
The project is designed and tested using simulation tools.

 Repository Files

This repository includes two main files:

Proteus Simulation File
This file contains the full circuit design and simulation of the refrigerator system using Proteus.

AVR Assembly Source Code (.asm)
This file contains the AVR Assembly program used to control the system (ADC reading + output control).

⚙️ How It Works (Assembly Logic)

The microcontroller reads the temperature input using the ADC.

Based on the ADC value, the program decides:

Turn Cooling (motor/relay) ON or OFF

Turn ON status LEDs (Cold / Normal / Hot)

Activate an Alarm/Buzzer when the temperature is too high (if included)

 Tools Used

Proteus (Circuit simulation)

AVR Simulator / AVR Assembler (to compile and run the .asm code)

How to Run

Open the Proteus file and load the compiled HEX file.

Run the simulation.

Change the sensor value (temperature input) to see the system response.
