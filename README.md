# Experiment 02 Implementation ofc ombinational logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
  Create a New Project:
        Open Quartus and create a new project by selecting "File" > "New Project Wizard."
        Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

  Create a New Design File:
        Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
        Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

  Write the Combinational Logic Code:
        Open the newly created Verilog or VHDL file and write the code for your combinational logic.

  Compile the Project:
        To compile the project, click on "Processing" > "Start Compilation" in the menu.
        Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

  Analyze and Fix Errors:*
        If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
        Review and fix any issues in your code if necessary.
        View the RTL diagram.

6.*Verification:

   Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
   Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
   Give the Input Combinations according to the Truth Table amd then simulate the Output Waveform.

## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
## RTL realization

## Output:
## RTL
F1

F2

## Timing Diagram
## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
