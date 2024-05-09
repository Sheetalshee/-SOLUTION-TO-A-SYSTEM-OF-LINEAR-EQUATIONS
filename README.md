
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
``` python
#Solution to a system of linear equation
#Devloped by: SHEETAL.R
#Ref.no: 212223230206
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
x=np.linalg.solve(a,b)
print(x)
```

## Output:

## Result: ![maths1](https://github.com/Sheetalshee/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/144979107/1de1a1cf-4ff4-4c98-b90c-9d11bb84ef64)

Thus the solutions for the linear equations are successfully solved using python program

