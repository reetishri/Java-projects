# Java-projects
Import statements: The code imports necessary classes for Swing components, fonts, colors, and event handling.
Class variables:
frmCalculator: A JFrame object representing the calculator's window.
result, expression: Strings to store the result and the current expression.
token: An ArrayList of Strings to store the postfix expression.
num, dot: Booleans to track whether a number or a decimal point is being entered.
main method: The entry point of the application, creates a Calculator object and makes its frame visible.
Calculator constructor: Initializes the calculator's GUI components and layout.
precedence method: Returns the precedence of an operator.
isoperator method: Returns true if the given string is an operator.
infixTopostfix method: Converts an infix expression to a postfix expression using the Shunting Yard algorithm.
factorial method: Calculates the factorial of a given number.
calculate methods: Perform binary and unary arithmetic operations.
Eval method: Evaluates a postfix expression and returns the result.
calculateMain method: Processes the user's input, converts the infix expression to postfix, evaluates it, and updates the display.
The rest of the code is the event handling and GUI setup for the calculator buttons.
The calculator has buttons for digits, arithmetic operators, functions like sin, cos, tan, log, ln, sqrt, and factorial, as well as clear (C), delete (DEL), and equals (=) buttons. The calculator supports basic arithmetic operations, as well as parentheses for grouping expressions. The display shows both the current expression and the result
