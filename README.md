# Simple Calculator using ATmega32

This project implements a basic calculator using the ATmega32 microcontroller, a 4x4 keypad, and a 2x16 LCD. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator takes input from the keypad and displays the result on the LCD in real-time.

## Features

### Basic arithmetic operations: addition, subtraction, multiplication, and division

### Input via 4x4 keypad

### Output displayed on 2x16 LCD

### Real-time calculation and display using ATmega32

## Components Used

### ATmega32 Microcontroller: The central processing unit for the calculator.

### 4x4 Keypad: Used to input numbers and operations.

### 2x16 LCD: Displays the entered numbers, operations, and results.

### GPIO: Used for connecting the keypad and LCD to the microcontroller.

## System Overview

### Keypad Input:

The 4x4 keypad is used to enter digits (0-9) and arithmetic operators (+, -,\*, /). The user can also input an equal sign ('=') to display the result.

### Microcontroller:

The ATmega32 handles the logic to process the input and perform calculations. It also controls the display on the LCD.

### LCD Output:

The 2x16 LCD shows the input numbers, selected operation, and the result after calculation.

## Functionality

### The user enters numbers and operations via the keypad.

### The microcontroller processes the inputs and calculates the result.

### The result is shown on the LCD in real-time.

## Wiring Connections

### Keypad: The 4x4 keypad is connected to the microcontroller's GPIO pins.

### LCD: The 2x16 LCD is connected to the microcontroller's GPIO pins.

### Microcontroller: The ATmega32 is the main controller for the system.

## How to Use

### Press the numeric keys (0-9) on the keypad to enter numbers.

### Use the operator keys (+, -, \*, /) for the desired arithmetic operation.

### Press the equal sign (=) to get the result.

### The result will be displayed on the LCD.

## Code Description

### The code is written in C and uses the AVR-GCC compiler. The main components of the code include:

#### GPIO Initialization:

Configures the GPIO pins for the keypad and LCD.

#### Keypad Scanning:

Reads inputs from the 4x4 keypad.

#### LCD Functions:

Functions to initialize the LCD and display the result.

#### Arithmetic Operations:

Functions to perform basic arithmetic operations.

## Dependencies

### AVR-GCC Compiler

### AVR Libc

### Atmel Studio (or any compatible IDE for AVR programming)

## License

This project is open-source
