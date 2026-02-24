THREE-PHASE POWER CALCULATOR

A C++ Engineering Project

Author: MOHAMED ABDULLAHI ABDI
Registration Number: FEE3/2701/2025
Department: Department of Electrical and Information Engineering
Institution: The University of Nairobi
Email: fee327012025@students.uonbi.ac.ke

1. PROJECT DESCRIPTION

This project is a Three-Phase Power Calculator developed in C++ to analyze balanced three-phase electrical systems.

The program allows the user to:

• Select the type of load connection (Star/Wye or Delta)
• Input line voltage, line current, and power factor
• Automatically compute phase values
• Calculate Active Power (P), Reactive Power (Q), and Apparent Power (S)
• Determine the phase angle (φ)
• Validate user inputs for correctness

The goal of this project is to demonstrate a clear understanding of three-phase power system theory and implement the mathematical principles into a working engineering tool.

This calculator can be used by electrical engineering students to quickly analyze balanced three-phase systems without performing manual calculations.

2. OBJECTIVES OF THE PROJECT

The main objectives of this project are:

To apply three-phase power system formulas in real computation

To implement Star and Delta conversion relationships

To compute P, Q, S, and Power Factor accurately

To validate user input for engineering correctness

To practice Object-Oriented Programming in C++

To present electrical results in a structured and professional format

3. ENGINEERING THEORY IMPLEMENTED

This program is based on balanced three-phase power system equations.

3.1 Line and Phase Relationships

For STAR (Wye) Connection:

V_phase = V_line / √3
I_phase = I_line

For DELTA Connection:

V_phase = V_line
I_phase = I_line / √3

These relationships are automatically handled by the program depending on user selection.

3.2 Power Calculations Used

The following standard three-phase formulas are implemented:

Apparent Power:

S = √3 × V_L × I_L (Volt-Amperes, VA)

Active Power:

P = S × Power Factor (Watts, W)

Reactive Power:

Q = S × sin(φ) (Volt-Ampere Reactive, VAR)

Phase Angle:

φ = cos⁻¹ (Power Factor)

All trigonometric calculations are handled using the C++ cmath library.

4. PROGRAM STRUCTURE

The project is written using Object-Oriented Programming principles.

Main components:

• Class: ThreePhaseSystem
• Member variables for electrical quantities
• Methods for:

Input handling

Phase value calculation

Power computation

Output display

The program flow is:

User selects connection type

User enters electrical values

Program validates power factor

Phase values are computed

P, Q, S, and φ are calculated

Results are displayed clearly

User may repeat calculation

5. INPUT VALIDATION

The program includes validation for Power Factor:

• If PF is entered below 0 or above 1
• The program automatically resets it to 1.0
• A warning message is displayed

This ensures physically meaningful electrical results.

6. FEATURES OF THE PROJECT

• Handles both Star and Delta systems
• Automatically performs line-to-phase conversions
• Computes:

Active Power (P)

Reactive Power (Q)

Apparent Power (S)

Phase Angle (φ)
• Displays results with two decimal precision
• Allows repeated calculations
• Organized and readable output formatting

7. SAMPLE CALCULATION FLOW

Example Input:

Connection Type: Star
Line Voltage: 400 V
Line Current: 10 A
Power Factor: 0.8

The program will compute:

Phase Voltage
Phase Current
Apparent Power (S)
Active Power (P)
Reactive Power (Q)
Phase Angle (φ in degrees)

All results are clearly labeled and formatted.

8. HOW TO COMPILE AND RUN

Requirements:

• C++ Compiler (g++, MinGW, or any standard C++ compiler)

Compilation:

g++ three_phase_calculator.cpp -o calculator

Execution:

./calculator

(Note: The screen clearing command uses "cls" which is Windows specific.)

9. WHY THIS PROJECT IS IMPORTANT

Three-phase systems are widely used in:

• Power generation
• Industrial motors
• Transmission systems
• Manufacturing plants

Understanding power calculations in Star and Delta systems is fundamental for every electrical engineer.

This project demonstrates:

• Strong understanding of power system fundamentals
• Application of mathematics in engineering
• Clean program structure
• Practical problem-solving ability

10. SKILLS DEMONSTRATED

• C++ Programming
• Object-Oriented Design
• Mathematical Modelling
• Engineering Computation
• Input Validation
• Clean Output Formatting
• Real-World Electrical Application

11. CONCLUSION

This Three-Phase Power Calculator successfully integrates electrical power system theory with C++ programming.

The project reflects practical understanding of:

• Balanced three-phase systems
• Star and Delta relationships
• Power triangle analysis
• Engineering computation techniques



Author:
MOHAMED ABDULLAHI ABDI
FEE3/2701/2025
Department of Electrical and Information Engineering
The University of Nairobi

