# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : DILIP KUMAR R 
 # REGISTER NUMBER :212225230059
 # DEPARTMENT : B.TECH AI&DS
 # YEAR :II
 # DATE :20.07.26

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
# AND GATE:
<img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/4d31b0be-606f-404e-8c68-ee1818707482" />

# OR GATE :
<img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/1d101d83-f2b8-44b8-9297-95a5ef205f3c" />


# NOT GATE :
<img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/76124c88-6f27-4420-b3c6-1fd8a311e2fa" />


# NAND :
<img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/050d9a41-dde2-46b3-94ea-cc19c1239396" />


# NOR :
<img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/c6991ea6-25cb-4059-aafa-67443a11363b" />


# XOR :
<img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/aa8a721a-950c-4f7d-8fc4-aa48f17996b8" />


 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
# AND GATE :
<img width="700" height="125" alt="image" src="https://github.com/user-attachments/assets/cd5565dd-6b3a-4e02-9486-4503d727afe4" />

# OR GATE :
<img width="701" height="209" alt="image" src="https://github.com/user-attachments/assets/0bb161eb-32d3-4dae-aa7b-50064f9a7ce3" />

# NOT GATE :
<img width="645" height="141" alt="image" src="https://github.com/user-attachments/assets/91df57cd-cac4-497c-b83a-49cabbf26ab7" />

# NAND GATE :
<img width="665" height="134" alt="image" src="https://github.com/user-attachments/assets/ec244caa-0ca5-4144-8b38-22cac6a73801" />

# NOR GATE : 
<img width="695" height="130" alt="image" src="https://github.com/user-attachments/assets/3a068032-f742-4f39-a54f-2d7b905aee2c" />


# XOR GATE : 
<img width="683" height="246" alt="image" src="https://github.com/user-attachments/assets/d7788b95-73ab-4da4-8419-0f2441c5c3ca" />

# DEVICE MONITOR TABLE :
<img width="1703" height="576" alt="image" src="https://github.com/user-attachments/assets/e031142c-4b9e-41f2-aa16-30dad096c9cf" />
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/1e158f91-a271-40cf-8677-2a1c40c7e064" />
<img width="1917" height="987" alt="image" src="https://github.com/user-attachments/assets/b2b69751-aab3-49ec-8503-997b541881cf" />
<img width="1917" height="993" alt="image" src="https://github.com/user-attachments/assets/5a139b34-1b26-4c57-8601-426abaa79654" />



# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
