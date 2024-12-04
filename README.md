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
import numpy as np

# Coefficients of the equations
A = np.array([
    [5, -3, -10],
    [2, 2, -3],
    [-3, -1, 5]
])

# Constants on the right-hand side
B = np.array([-9, 4, -1])

# Solve the system of equations
solution = np.linalg.solve(A, B)

# Print both the raw and formatted solution
print( solution)
x, y, z = solution
#print(f"The formatted solution is: x = {x:.2f}, y = {y:.2f}, z = {z:.2f}")
```
## Output:
![image](https://github.com/user-attachments/assets/f5dea271-650c-4d89-98ee-a80a5c2d5112)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

