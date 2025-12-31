# Love Calculator
The Love Calculator is a simple Python application built using the Tkinter library to create a GUI. It calculates a random "love percentage" between you and your partner based on their names. It uses the random module to generate a love percentage between 0 and 99.

# Features
A GUI built using Tkinter.<br>
Users input their name and their partner's name.<br>
A random love percentage is generated and displayed on the screen.<br>
Simple, interactive, and fun calculator for romantic purposes!

# Installation
To run the Love Calculator, you need to have Python installed on your computer. The application uses the Tkinter library, which is typically included with Python by default.
# Steps to Install and Run the Project:

# 1.Clone the repository (or download the code files):
git clone https://github.com/yourusername/love-calculator.git

# 2.Navigate to the project directory:
cd love-calculator

# 3.Run the Python script:
python love_calculator.py


The Love Calculator GUI window should open, where you can input your name and your partner's name and calculate the love percentage.

# Code Explanation
# Main Components:

**Tkinter**: The GUI toolkit that is used to create the window and various widgets (labels, buttons, etc.).<br>
**random.sample()**: This function generates a random love percentage by picking two digits (0-9).<br>
**Labels and Entry Widgets**: Used to display information and accept user inputs (name1 and name2).<br>
**Button**: When clicked, it triggers the calculate_love() function that generates the random love percentage.

# Core Functionality:
The function calculate_love() generates a random two-digit number representing the "love percentage" and updates the result label with that value.

# Usage

**1.** Input your name and your partner's name in the text fields.<br>
**2.** Click the "Calculate" button to get a random love percentage.<br>
**3.** The result will be displayed in the form of a love percentage.<br>

# Example:
Enter Your Name: John<br>
Enter Your Partner Name: Sarah<br>
Love Percentage between both of You: 47%<br>

# Requirements

Python 3.x<br>
Tkinter (Usually bundled with Python)
