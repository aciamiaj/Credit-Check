# Credit-Check

The Credit Check is a console application that allows users to check the credit limit for a customer based on their chosen method: online or offline. The program prompts the user to select a check method, enter a customer ID, and then displays the credit limit based on the chosen method.

## Code Overview
The provided code snippet includes the following components:

User Input: The program prompts the user to select a check method by displaying options from the CreditCheckFactory singleton. The user is also asked to enter a customer ID.

Credit Limit Check: The code creates an instance of the CreditCheckFactory and uses it to determine the appropriate ICreditCheck implementation based on the chosen method. The ICreditCheck object is used to calculate and display the credit limit for the given customer ID.

## Usage
To use the Credit Check, follow these steps:

Ensure that the necessary dependencies are included and the required classes (CreditCheckFactory and ICreditCheck) are available.

Run the code in a console application environment.

The program will display the student's name and Humber ID.

The program will ask the user to choose the desired method for checking the credit limit.

The available options will be displayed, and the user should enter the corresponding option.

The program will prompt the user to enter the customer ID for whom they want to check the credit limit.

Based on the chosen method, the program will calculate and display the credit limit for the given customer ID.

The program will terminate after displaying the credit limit.

## Notes
Please note that the provided code snippet is a simplified implementation of the Credit Check. In a real-world scenario, additional functionalities such as data validation, error handling, and integration with external systems may be required.
