# Calculator-projects
Calculator project using different files for different classes
Main.java contains the main method, which is the entry point for the program.
It creates an instance of UserInput and Calculator classes, and enters into an infinite loop that reads user input, performs calculations using the Calculator class, and prints the result.
The loop continues until the user enters the "exit" command.


UserInput.java contains a class that is responsible for handling user input.
It contains three methods which are:
getOperation() prompts the user to enter an operation, reads the input from the console, and returns the operation as a string.
getDouble() prompts the user to enter a number, reads the input from the console, and returns the number as a double.
getDoubleArray() prompts the user to enter an array length, reads the length from the console, prompts the user to enter the elements of the array, reads the elements from the console, and returns the array as an array of doubles.


Calculator.java:
This file contains a class that is responsible for performing the calculations.
It contains methods for performing the basic arithmetic operations (addition, subtraction, multiplication, and division), as well as methods for calculating the sum, variance, and standard deviation of an array of doubles.
The calculate() method takes an operation as a string and a UserInput object as parameters, and performs the appropriate calculation based on the operation and user input. It returns the result of the calculation as a double.
