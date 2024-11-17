# **Bit Serial Adder Subtractor FSM**

This repository contains the lab report, design files, and simulation results for the **Bit Serial Adder Subtractor with an Accumulator System**, developed as part of the Digital Systems I course at RIT.

## **Overview**
This project demonstrates the design and implementation of a **Bit Serial Adder Subtractor** controlled by a **Finite State Machine (FSM)**. Using 5-bit operands, the system performs serial addition and subtraction, integrating key digital design concepts such as shift registers, two's complement arithmetic, and Boolean algebra.

The project was implemented using **Intel Quartus** for circuit synthesis and **ModelSim** for waveform simulation, showcasing practical skills in FPGA-based system design and verification.

---

## **Features**
- **Finite State Machine (FSM)**:
  - Serves as the control unit.
  - Implements addition and subtraction based on input signals.
- **Shift Registers**:
  - Stores operands (X and Y).
  - Performs bitwise operations.
- **Bit Serial Adder**:
  - Adds or subtracts bits serially using a Full Adder.
  - Handles two's complement subtraction via XOR gates.
- **Waveform Analysis**:
  - Verifies system functionality through detailed simulation waveforms.

---

## **Project Components**
1. **Lab Report**:
   - Comprehensive documentation of the project.
   - Includes block diagrams, Karnaugh maps, and waveform results.
2. **FSM Design**:
   - Detailed state diagram and state assignment tables.
3. **Simulation Files**:
   - Waveform diagrams from Quartus and ModelSim for system validation.
4. **Optimized Boolean Logic**:
   - Karnaugh maps for minimizing logic gate usage.

---

## **Technologies Used**
- **Intel Quartus**: Circuit design, synthesis, and verification.
- **ModelSim**: Waveform simulation and analysis.
- **Digital Logic Concepts**: Karnaugh maps, Boolean algebra, and two's complement arithmetic.

---

## **How to Use**
1. **View the Lab Report**:
   - Access the detailed report in `lab_report.pdf`.
2. **Analyze the Block Diagrams**:
   - Review FSM, shift registers, and adder designs for a clear understanding of the system.
3. **Simulate the Circuit**:
   - Use Quartus to open the provided design files and ModelSim to run simulations.
4. **Verify Outputs**:
   - Compare simulation waveforms with expected results as outlined in the lab report.

---

## **Waveform Highlights**
- **FSM Functionality**:
  - Correct assertion of addition or subtraction outputs based on control signals.
- **Shift Register Behavior**:
  - Proper shifting and bit loading operations during addition and subtraction.
- **Bit Serial Adder**:
  - Accurate handling of carries and two's complement subtraction.

---

## **Results**
The circuit successfully performed serial addition and subtraction of 5-bit operands, demonstrating:
- Precise control by the FSM.
- Correct logic gate minimization via Karnaugh maps.
- Proper waveform outputs matching theoretical expectations.

---
