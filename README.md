# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim: To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 Step 1: Import the numpy module to use the built-in functions for calculation
 Step 2: Prepare the lists from each linear equations and assign in np.array()
 Step 3: Using the np.linalg.solve(), we can find the solutions.
 Step 4: End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Shalini.k
#RegisterNumber:212222240095
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
soln=np.linalg.solve(A,B)
print(soln)
```
## Output:
![image](https://github.com/shalinikannan23/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/118656529/e898297f-4b07-406e-a340-8ab9ccbeed22)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

