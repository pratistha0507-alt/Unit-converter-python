# Unit-converter-python
A feature-rich console-based universal unit converter (length, weight, temperature) with input validation and modular design. Made by Pratistha Aggarwal, VIT Bhopal 2025
Project Title: Unit Conversion using Python
Unit Converter Application (Python)

A simple, interactive console-based Unit Converter built using pure Python that converts between common units of Length, Weight, and Temperature. This project demonstrates core Python concepts such as functions, loops, conditionals, input validation, and modular design.

Submitted by: Pratistha Aggarwal
Institution: Vellore Institute of Technology, Bhopal  
Year: 2025

 Overview

Project Overview

The Unit Converter Application is a menu-driven Python program that allows users to easily convert values between commonly used units in three categories:

- Length: meter (m), centimeter (cm), kilometer (km), mile, foot, inch  
- Weight/Mass: gram (g), kilogram (kg), pound (lb), ounce (oz)  
- Temperature: Celsius (°C), Fahrenheit (°F), Kelvin (K)

The tool is accurate, fast, lightweight, and requires no external libraries— perfect for learning and daily use.




 Features

- Supports bidirectional conversions in Length, Weight, and Temperature
- Clean interactive menu system
- Input validation (only accepts numeric values)
- Error handling using try-except
- Continuous operation — perform multiple conversions without restarting
- Clear output with proper unit labels
- Modular functions for easy maintenance and future expansion
- 100% pure Python — runs anywhere Python is installed


















Technologies & Tools Used

- Language: Python 3.x
- Standard Library Only (no external packages)
- Concepts Used:
  - Functions
  - Dictionaries for unit mapping
  - while loops & conditionals
  - try-except for error handling
  - f-strings for formatted output


















Installation & Run the Project

Prerequisites
- Python 3.6 or higher installed on your system


Steps to Run
1. Clone the repository
git clone https://github.com/your-username/unit-converter-python.git
cd unit-converter

 2. Navigate to project folder
cd unit-converter

3. Run the application
python unit_converter.py
 or
python3 unit_converter.py
The program will start immediately with an interactive menu.









Example Session
text
=== Unit Converter ===
1. Length Conversion
2. Weight Conversion
3. Temperature Conversion
4. Exit

Enter your choice: 1
Enter value in meters: 1500
1500.0 meters = 1.5 kilometers
1500.0 meters = 4921.26 feet
1500.0 meters = 59055.12 inches

Convert another? (y/n): y













Instructions for Testing
The application includes built-in input validation and error handling.
Manual Testing Recommendations:
1.	Test with valid numbers → should convert correctly
2.	Test with invalid input (letters, symbols) → should show friendly error and reprompt
3.	Test edge cases (0, negative values where applicable, very large numbers)
4.	Test exiting and continuing the loop
Example of error handling:
text
Enter value in kg: abc
Invalid input! Please enter a numeric value.
















Screenshots
 


Future Enhancements
•	Add Graphical User Interface (using Tkinter or PyQt)
•	Support more unit categories (Volume, Area, Speed, Time, etc.)
•	Add history of recent conversions
•	Export results to a file
•	Voice input/output support
•	Package as a mobile or web app





Learnings & Takeaways
•	Strengthened understanding of Python functions and modular programming
•	Learned proper input validation and exception handling
•	Gained experience in building user-friendly console interfaces
•	Understood real-world application of conversion formulas


