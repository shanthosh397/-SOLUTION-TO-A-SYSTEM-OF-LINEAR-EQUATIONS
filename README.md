DATE:16-03-2024
# SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Write a program to find a solution to a system of linear equations 5x-3y-10z=-9, 2x+2y-3z=4, -3x+y+5z=-1
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,1,5]])
B = np.array([-9,4,-1])
solution = np.linalg.solve(A,B)
print("The solution for the given matrix is",solution)
## Output:
![Screenshot 2024-04-07 230632](https://github.com/shanthosh397/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/153431200/9e9d7365-a5f0-45cd-80ab-ac1e1aadcb6f)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

