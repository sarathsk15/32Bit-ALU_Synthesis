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

Program :


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
![Screenshot (18)](https://github.com/user-attachments/assets/6e495b6a-81b9-4f9d-980d-1abb5cca3319)

#### Area report:
![Screenshot (20)](https://github.com/user-attachments/assets/3ff77101-3dca-40f6-8755-a4f364b247e7)

#### Power Report:
![Screenshot (22)](https://github.com/user-attachments/assets/ba3bc2ce-9f2c-4fb0-81ad-6dcce4dee113)

#### Gates report:
![Screenshot (21)](https://github.com/user-attachments/assets/37eaf0ee-bb76-49cc-a0dd-3352bf656bcd)

#### Timing report:
![Screenshot (23)](https://github.com/user-attachments/assets/1a07cef3-a65c-4d5c-a8de-ac6d456cd2d5)



#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
