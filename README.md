# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![439800413-241052f7-c451-463e-92bd-9e2ccd1842e2 (1)](https://github.com/user-attachments/assets/f5d0de52-2683-4795-9795-2fec9ee130d7)

### Schematicand Symbol of 2-Input EX-OR Gate:

![439800474-f5dce6e6-7934-49e9-bdc7-8475d90dd809](https://github.com/user-attachments/assets/12e31287-5286-411a-bf6c-ab0c79d84ecf)

### Schematicand Symbol of Half Adder:
![439800524-b7be0d9b-70e4-4d81-b0bc-99f29f3b60e5](https://github.com/user-attachments/assets/5a745dbe-60ae-4d57-bf7f-ba6dbc47d507)

### Schematic of 2-Bit Multiplier:
![439800598-0f37bb9a-7418-408c-93aa-e47760dcf713](https://github.com/user-attachments/assets/3425dcf2-34f8-4bb0-b81c-ba252b65b90d)

## Output
### Transient Analysis Output:
![445914347-ef3b83a5-e1a3-45f1-b565-8459b54da50d](https://github.com/user-attachments/assets/d315fed9-c41c-4b46-b605-8658092159fe)

Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
