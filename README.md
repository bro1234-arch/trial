#description
In num.c, the sum is calculated as sum = num1 + num3;, but the variable num3 is not defined or initialized anywhere . This will result in a compilation error and undefined behavior.

#why it this issue must be fixed

It needs to be fixed to ensure program efficiency and remove compilation errors.

#Steps to Reproduce:

-Compile num.c.
-Observe the compilation error indicating 'num3' is undeclared.
-failed code execution

#Additional info

Fixing this will allow the program to compile and function as intended.

title Undefined variable 'num3' used ( in num.c file )  

---------------------------------------------------------------------------------

for issue 

modified variables and logic of calculation
1.What is the type of the Pull request:

/kind Enhancement

2.what does this Pull request do :
It will calculate the sum of variables 'a' and 'b' in the code and assign the values to "sum"

Which issue will it fix:
Invalid Datatype and wrong calculation logic

4..Test report added:
/kind not tested

5.test report:
No test report link since the code is not tested.
