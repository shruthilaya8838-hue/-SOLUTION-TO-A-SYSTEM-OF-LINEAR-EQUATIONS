# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:05-02-2026
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
~~~
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
X=np.linalg.solve(A,B)
print(X)
~~~
## Output:
<img width="612" height="300" alt="image" src="https://github.com/user-attachments/assets/20e87d40-0e65-4e62-8d6c-aac79aaa1e9b" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

