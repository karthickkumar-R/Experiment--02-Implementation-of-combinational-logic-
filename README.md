# NAME      :KARTHICKKUMAR.R

# ROLL NO   :23012023

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

1. Create a New Project: Open Quartus and create a new project by selecting "File" > "New
   Project Wizard." Follow the wizard's instructions to set up your project, including specifying the
   project name, location, and target device (FPGA).
2. Create a New Design File: *Once the project is created, right-click on the project name in the
   Project Navigator and select "Add New File." *Choose "Verilog HDL File" or "VHDL File,"
   depending on your chosen hardware description language.
3. Write the Combinational Logic Code: *Open the newly created Verilog or VHDL file and write
   the code for your combinational logic.
4. Compile the Project: *To compile the project, click on "Processing" > "Start Compilation" in the
   menu. *Quartus will analyze your code, synthesize it into a netlist, and perform optimizations
   based on your target FPGA device.
5. Analyze and Fix Errors:* *If there are any errors or warnings during the compilation process,
   Quartus will display them in the Messages window. *Review and fix any issues in your code if
   necessary. *View the RTL diagram. 6.Verification: *Click on "File" > "New" >
   "Verification/Debugging Files" > "University Program VWF". *Once Waveform is created Right
    Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On
   "List" > Select All. *Give the Input Combinations according to the Truth Table amd then
    simulate the Output waveform

# Program:

![wo2 p](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/b968bd7d-936b-463b-929e-d57439f089ad)

# RTL realization

![wo2 lg](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/a80af579-409c-4945-9b5e-edf16e50ad25)

# TRUTH TABLE

![wo2 tt](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/8a1ad46a-9e4d-4dd8-86e9-f57be994f129)

# Timing Diagram

![wo2 td](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/150005103/f75cb728-4e2e-4942-82bf-8266e591d49c)

# Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
