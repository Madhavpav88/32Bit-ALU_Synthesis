# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![Screenshot (55)](https://github.com/user-attachments/assets/d3ad42fc-faaa-4c9f-8209-ac87754b56b4)

#### Area report:
![Screenshot (56)](https://github.com/user-attachments/assets/ade12b28-02c9-4149-a2b2-c25bb605d97a)

#### Power Report:
![Screenshot (57)](https://github.com/user-attachments/assets/2281d5ae-d8a8-480d-801f-a651768871e8)
![Screenshot (58)](https://github.com/user-attachments/assets/410a5569-21ab-46d7-b448-9a892eb5cad6)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
