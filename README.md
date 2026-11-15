# Water Level Detector using LM358

## Overview
This project is a water level detector built on a PCB. Using the circuit design, I placed all the components on the board, soldered them and tested the water detection. An LM358 op-amp works as a comparator. It compares the sensor signal with a reference voltage set by a trimmer pot. When the water level is detected, the output LED turns on and the relay switches.

![Water Level Detector Board](board.jpg)

## Features
- Water level detection using an LM358 comparator
- Adjustable detection level using a trimmer pot
- Relay output with NC, C and NO terminals to switch an external load
- LED indicators for power, relay and output status
- 5V supply input through a 2-pin header
- Hand-soldered single-sided PCB

## Components Used
- LM358 op-amp
- Trimmer pot
- NPN transistor (relay driver)
- 5V relay (JQC-3FC)
- 1 red LED and 2 green LEDs
- 10k resistors
- 2-pin header

## How It Works
1. The sensor signal is given to one input of the LM358.
2. The trimmer pot sets the reference voltage on the other input.
3. When the sensor voltage goes above the reference, the comparator output switches.
4. The transistor turns on and the relay pulls in.
5. The output LED turns on and the relay contacts switch the external load.

## What I Did
- Placed all the components on the PCB as per the circuit design
- Soldered every component by hand
- Checked the connections and tested the water detection

## Result
Whenever the water reaches the probe level, the circuit detects it. The output LED turns on and the relay switches.

## Future Improvements
- Enclosure for the board
- Buzzer alarm output
- Sturdier probe connector

## Author
Pallavi Doddamani
B.E. Electronics and Communication Engineering
BMS College of Engineering
