🧮 Simple Calculator

A basic Python program that performs simple arithmetic operations — addition, subtraction, multiplication, and division — based on user input.

📋 Features

Supports the four fundamental operations: +, -, *, /

Interactive command-line interface

Easy to modify or extend

🚀 How to Run

Clone this repository:

git clone https://github.com/yourusername/simplecalculator.git
cd simplecalculator


Run the program:

python simple\ calculator.py


Follow the prompts:

enter your choice +,-,*,/
enter first number: 10
enter second number: 5
Result: 15

🧠 Example
enter your choice +,-,*,/
+
enter first number: 12
enter second number: 8
Result: 20

🧩 Code Overview

The program uses simple conditional statements (if, elif, else) to determine which operation to perform.

Example snippet:

choice = input("enter your choice +,-,*,/: ")
num1 = float(input("enter first number: "))
num2 = float(input("enter second number: "))

if choice == '+':
    print("Result:", num1 + num2)
elif choice == '-':
    print("Result:", num1 - num2)
elif choice == '*':
    print("Result:", num1 * num2)
elif choice == '/':
    print("Result:", num1 / num2)
else:
    print("Invalid input")

🛠 Requirements

Python 3.6 or higher (works with Python 3.13 too)

📄 License

This project is open-source and available under the MIT License
