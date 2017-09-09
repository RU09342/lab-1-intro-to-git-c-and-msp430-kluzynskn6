# Information on math.c and math.h

## math.c
This file includes the math function. This function allows the user to do a variety of math comands on two numbers. \newline
To use the function, you need 2 numbers and an operator. The accepted operators are as follows:

 (addition)       +  \newline
 (subtraction)    -  \newline
 (multiplication) *  \newline
 (division)       /  \newline
 (exponent)       ^  \newline
 

When calling the function, use the following format: math(number 1, number 2, operator). \newline
In cases where the result is depenedant on the order of the numbers, number 1 is always placed first.
ex: math(4,1,-) is equivalent to 4-1

## math.h
This header file needs to be included with math.c in order to define it as a proper function.