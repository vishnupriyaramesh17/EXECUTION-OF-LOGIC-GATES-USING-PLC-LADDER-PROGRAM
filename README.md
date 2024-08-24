# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : Vishnu priya R
 # REGISTER NUMBER : 212222110054
 # DEPARTMENT : CSE(IOT)
 # YEAR : 3rd

 
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
# AND:
 ![361132260-eea60067-c686-42ee-a48c-617aa6e32e05](https://github.com/user-attachments/assets/3316f8a7-b5a3-4c23-84a3-f3908f6d1ad9)
# OR:
![361132264-0422b9e6-0997-496e-9fd3-167ee152811a](https://github.com/user-attachments/assets/fad56ee5-2df6-4b6b-a2b5-cbbc0d134d09)

# NAND:
![361132277-e73d68db-858b-4a03-aa9f-a9c1be38009f](https://github.com/user-attachments/assets/47d9b70f-c62c-4d0c-95d5-57d4e40345fd)

# NOT:
![361132270-ba15263c-2c3f-4fd3-bf70-c7a739d7639e](https://github.com/user-attachments/assets/07e27fba-3a5c-414d-bb0b-f79a0ea24dad)

# XOR:
![361132277-e73d68db-858b-4a03-aa9f-a9c1be38009f](https://github.com/user-attachments/assets/bb276da3-9095-4b20-94bd-df77a7d36da5)

# NOR:
![360789440-e571e579-5afa-4527-b399-e48737f96b9f](https://github.com/user-attachments/assets/4d1ccfd2-7d03-4121-808b-ca8df564ecd8)

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

# AND:
![360789795-bcdfdaf4-f782-4f15-9246-74a746f51459](https://github.com/user-attachments/assets/a7b4ff0a-f00a-466c-8425-ce8ac80e7ab9)

# OR:
![360789806-35307301-fcaf-41cc-a7e7-b230152b32d9](https://github.com/user-attachments/assets/26f2adbe-5fbf-4c53-a3c6-e5fe7adb2243)

# NAND:
![360789867-adad979e-7ab1-48a4-98f3-919ab8073633](https://github.com/user-attachments/assets/c3e24a17-7db5-41b3-8af7-50f903e6e2c7)

# NOT:
![360789849-3b244ac8-0679-447a-8929-38dbe237e90b](https://github.com/user-attachments/assets/a209d239-4188-4971-a623-39d2791340a0)

# XOR:
![360789819-236d97f4-0514-499a-9098-262980b93211](https://github.com/user-attachments/assets/e1a56c97-8ab8-4936-b09e-c1d7d4f10073)

# NOR:
![360789835-a1c7c759-4d60-43df-93a9-700cbf9a9791](https://github.com/user-attachments/assets/b991aded-fef0-42b0-b339-e8e68a429a79)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
