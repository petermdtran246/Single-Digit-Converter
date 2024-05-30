# Single Digit Converter

This project provides a C++ program that converts a single-digit integer (0-9) to its corresponding written word.

## Algorithm:

1. Function Definition:

The program defines a function named DigitToWord that takes an integer d as input.

2. Conditional Statements:

The DigitToWord function uses a series of if-elif statements to check for specific digit values (0 to 9).
If a match is found, the corresponding written word ("one", "two", etc.) is printed using cout.

3. User Input and Function Call:

In the main function:
  -  An integer variable d is declared to store the user-provided digit.
  -  The program prompts the user to enter a single digit (0-9) using cout.
  -  The user's input is read from the console using cin and stored in the d variable.
  -  The DigitToWord function is called with the d value as an argument. This triggers the conversion logic based on the entered number.
