Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

Tools Required
Cadence EDA Suite
Virtuoso Schematic Editor (for circuit design)
Spectre Simulator (for circuit simulation)
Process Design Kit (PDK)
CMOS technology library (e.g., 180nm, 45nm node)
Computer System
Minimum 4GB RAM and a multi-core processor
Procedure:
1. Launch Cadence Virtuoso Environment:
 Open the Cadence Virtuoso tool and set up the working library.
 Create a new schematic cell view for the CMOS Inverter design.
2. Schematic Design:
Select the NMOS and PMOS transistors from the library.
Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
Join the gate terminals of both transistors to form the input node.
Connect input voltage sources Vdc and Vpulse
3. Simulation:
Check the Design for Errors and proceed for Simulation
Launch the Analog Design Environment (ADE).
Configure transient analysis for time-domain response.
Set the simulation parameters such as voltage sweep range and step size.
Use Spectre simulator to perform transient and DC analyses.
4. Waveform Analysis:
Observe the output voltage waveform concerning the input voltage.
Circuit Diagram:
1. Schematic of CMOS Inverter:
   
![Screenshot 2025-02-28 141546](https://github.com/user-attachments/assets/e6ec2356-7431-40db-847f-6bc4943a2d10)


2. Transient Response Setup:
   
![Screenshot 2025-02-28 141613](https://github.com/user-attachments/assets/6d119102-825e-4a24-860f-e0c542056cdc)

3. Voltage Transfer Characteristic (VTC) Setup:
![Screenshot 2025-02-28 141601](https://github.com/user-attachments/assets/f62d12d7-3ed6-4e06-9b3d-3f64ec9a6ff0)


Output
1.Transient Analysis Output

![Screenshot 2025-02-28 141513](https://github.com/user-attachments/assets/4ca1d1ee-a39c-4d84-b508-c2628264fdc7)


2.DC Analysis Output

![image](https://github.com/user-attachments/assets/4580def0-922d-4f4c-bb53-b7c145dd2e76)


Results:
Successfully designed the CMOS inverter schematic using Cadence EDA tools.
The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.
About
Academic Cadence Experiments
