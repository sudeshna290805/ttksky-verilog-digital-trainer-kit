<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is a Digital Trainer Kit designed using Wokwi and logic gates. It takes two input switches (IN0, IN1) and a set of selection bits (IN2–IN4) to choose a logic gate operation (AND, OR, XOR, NAND, NOR, etc.). The selected gate processes the inputs, and the result is sent to both:

OUT0: A digital output pin for observing the logic result directly.

7-segment display (OUT1–OUT7): Displays 0 when the output is LOW and 1 when the output is HIGH.

This simulates a real digital trainer kit used in labs, where students can experiment with different logic functions and visualize the results instantly.

## How to test

Set inputs IN0 and IN1 using switches in Wokwi.

Use selection bits IN2–IN4 to choose the gate you want to test:

Example: 000 = AND, 001 = OR, 010 = XOR, etc.

Observe:

OUT0 → Direct logic output.

7-segment display → Shows 0 or 1 based on the output.

Verify that the display matches the expected truth table of the selected gate.

## External hardware

7-segment display (common cathode) connected via output pins OUT1–OUT7.

Input switches for IN0 and IN1.

Selection switches for choosing logic gates.
