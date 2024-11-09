# Calculator Project

## Description
A Java-based console calculator application cable of performing both basic and advanced mathematical operations. This program allows users to select  the type of calculation (whether its basic or advanced) and provides a simple  yet interactive prompt to enter values and display results. The calculator handles basic opertations like addition, subtraction, multiplication, and division as well as advanced operations like power and square root calculations. (More to be added)

## Features
- **Basic Calculations**: Addition, Subtraction, Multiplication, Division
   - Can Handle division errors when dividing by zero
- **Advanced Calculations**: Power and Square Root
   - Can handle errors for square roots of negative numbers
- **Clear and Interactive Prompts**: Guides users through selecting the type of calculation and entering values.
- **Polymorphic Design**: Uses an abstract 'Calculator' class with a polymorphic 'display' for a clean, flexible, and modular display.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Maximiliano-RA/SoloCalculatorApp.git

2. **Navigate to the Project Directory**
   cd CalculatorProject

3. **Compile the Java Files**
   javac Main.java BasicCalculation.java AdvancedCalculation.java Calculator.java

4.**Run the Application**
  java Main
