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
#Developed by:paul shervin p
#RegisterNumber:24901141
import numpy as np
A=([[1,3],[2,5]])
B=([5,-3])
result=np.linalg.solve(A,B)
print(result)
```
## Output:

![image](https://github.com/user-attachments/assets/77fbecea-d75b-48e4-a472-696bf6af7fe2)




## Result: 
Thus the solutions for the linear equations are successfully solved using python program

