# PHP Ternary Operator Null Value Comparison
This repository demonstrates a subtle bug in PHP involving the ternary operator and null value comparisons.  The code uses a ternary operator to check if a GET parameter is set.  If it's not set, the variable is assigned null; otherwise it's assigned the parameter's value.
Then, another ternary operator attempts to check if the variable is null and print appropriate messages.  However, the comparison is done incorrectly. 
The bug is related to how PHP handles null values and string comparisons within ternary expressions. The solution demonstrates how to accurately check for null values and avoid the unexpected behavior.
