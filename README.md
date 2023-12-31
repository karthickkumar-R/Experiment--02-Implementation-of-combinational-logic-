# NAME    :KARTHICKKUMAR.R

# ROLL NO :23012023

# Experiment 02 Implementation of combinational logic

# AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

# Equipments Required:

 Hardware – PCs, Cyclone II , USB flasher
 Software – Quartus prime


# Theory

A combinational circuit is a circuit in which the output depends on the present combination of
inputs. Combinational circuits are made up of logic gates. The output of each logic gate is
determined by its logic function. Combinational circuits can be made using various logic gates,
such as AND gates, OR gates, and NOT gates.
 

# Procedure

1. Create a New Project:
   Open Quartus and create a new project by selecting "File" > "New Project Wizard."
   Follow the wizard's instructions to set up your project, including specifying the project
   name, location, and target device (FPGA).

2. Create a New Design File:
   *Once the project is created, right-click on the project name in the Project Navigator and
    select "Add New File."
   *Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description
    language.
   
4. Write the Combinational Logic Code:
   *Open the newly created Verilog or VHDL file and write the code for your combinational
    logic.
   
6. Compile the Project:
   *To compile the project, click on "Processing" > "Start Compilation" in the menu.
   *Quartus will analyze your code, synthesize it into a netlist, and perform optimizations
    based on your target FPGA device.
   
8. Analyze and Fix Errors:*
   *If there are any errors or warnings during the compilation process, Quartus will display
    them in the Messages window.
   *Review and fix any issues in your code if necessary.
   *View the RTL diagram. 6.Verification:
   *Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
   *Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" >
    Click on Node Finder > Click On "List" > Select All.
   *Give the Input Combinations according to the Truth Table amd then simulate the Output
    waveform

# Program:

![wo2 p](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/8c6c8065-9079-49a3-b629-14eda6dbf2d7)

# RTL realization

![wo2 lg](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/f0df87cd-64d7-4755-b858-e1ca8b48e2d6)

# TRUTH TABLE

![wo2 tt](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/fac20999-2854-4ba0-9624-8ee1a1d25791)

## Timing Diagram

![wo2 td](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/2185758d-d726-4dd2-bf7a-aa38ec57a174)

# Result:

Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
