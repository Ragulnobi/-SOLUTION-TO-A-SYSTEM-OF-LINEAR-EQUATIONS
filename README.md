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
```python
#Program to find the solution for the given linear equations.
#Developed by: Ragul R
#RegisterNumber:22003877
import numpy as np
A=[[1,-3],[3,1]]
B=[0,10]
sol=np.linalg.solve(A,B)
print(sol)
```

## Output:
![Screenshot 2023-01-23 230406](https://user-images.githubusercontent.com/121609342/214109647-24428040-fd4d-458b-885f-9696bb58efe3.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

