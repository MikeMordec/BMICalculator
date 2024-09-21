BMICalculator
Overview

BMICalculator is a simple Python program that calculates the Body Mass Index (BMI) based on the user's input of weight (in pounds) and height (in inches). It also provides a classification of the user's weight status: Underweight, Optimal, or Overweight, based on the calculated BMI value.
Features

    Accepts user input for weight (in pounds) and height (in inches).
    Calculates BMI using the formula: BMI = (weight * 703) / height^2.
    Classifies BMI into the following categories:
        Underweight: BMI < 18.5
        Optimal: 18.5 ≤ BMI < 25
        Overweight: BMI ≥ 25
    Includes error handling for invalid inputs.

Prerequisites

To run this Python program, you need:

    Python 3.x installed on your system.

Installation

    Clone the repository to your local machine:

    bash

git clone https://github.com/your-username/BMICalculator.git

Navigate to the project directory:

bash

    cd BMICalculator

Usage

    Run the BMICalculator.py file:

    bash

    python BMICalculator.py

    Follow the on-screen instructions to input your weight and height.

Example

bash

Enter your weight in pounds: 150
Enter your height in inches: 65
BMI: 24.96
Optimal

Error Handling

    The program ensures that both weight and height are positive numeric values.
    It prompts the user if non-numeric or invalid values are entered.

