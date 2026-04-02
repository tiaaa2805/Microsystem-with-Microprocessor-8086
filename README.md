# Microsystem-with-Microprocessor-8086

# 1. Project Overview
   The objective of this project is to design a microsystem based on the Intel 8086 microprocessor. The system integrates memory components and various I/O interfaces to perform serial/parallel communication, user input handling, and data display.
# 2. Hardware Specifications
   The microsystem must include the following hardware architecture:
     -Central Processing Unit:
     -Intel 8086 microprocessor.
     -EPROM Memory: 128 KB using 27C512 chips.
     -SRAM Memory: 64 KB using 62256 chips.
     -Serial Interface: 8251 controller, mapped to address zones 04D0H – 04D2H or 05D0H – 05D2H depending on the S1 switch position.
     -Parallel Interface: 8255 controller, mapped to address zones 0250H – 0256H or 0A50H – 0A56H depending on the S2 switch position.
     -Peripherals:A 9-contact mini-keyboard.
     -10 LEDs.
     -An 8-digit 7-segment display module (up to 8 hex characters).
     -A 2x16 character LCD module.3.
# 3.Software Requirements
  All programs must be written in Assembly language as subroutines. The required routines include:Initialization and programming for the 8251 and 8255 circuits.Character transmission and reception for the serial interface.Character transmission for the parallel interface.Mini-keyboard scanning routine.LED control (on/off).Hexadecimal character display for the 7-segment module.
# 4. Documentation Structure
     The final electronic folder must be organized as follows:
        Page 1: Identification details (University, Faculty, Discipline, Author, Academic Year).
        Page 2: Project theme.Hardware Description: 3–5 pages detailing the architecture.
        Software Listing: 3–7 pages of code with clear delimiters and comments.
        Schematics: Created using CAD software (e.g., EasyEDA, Proteus, OrCAD) in A4 or A3 format.
        Bibliography: Cited according to specific formatting rules.
