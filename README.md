# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
```
#Program to find the solution for the given linear equations.
#Developed by: G Dario 
#RegisterNumber: 22008843
import numpy as n
a=n.array([[1,-3],[3,1]])
b=n.array([0,10])
result=n.linalg.solve(a,b)
print(result)
```
## Output:
![ex1-solutions](https://user-images.githubusercontent.com/118704873/209903056-8ac443e3-e75f-4640-accc-3f9de3b8ea1d.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

