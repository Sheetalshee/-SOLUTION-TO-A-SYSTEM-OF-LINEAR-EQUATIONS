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
## Program:#Program to find the solution for the given linear equations.
#Developed by:R.Sheetal
#RegisterNumber:212223230206
import numpy as np
a=[[5,-3,-10],
   [2,2,-3],
   [-3,-1,5]]
b=np.array([-9,4,-1])
c=np.linalg.solve(a,b)
print(c)

## Output:
![image](https://github.com/sheetal.R/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150005194/934d403c-7ab0-4e02-92d5-3728065ab852)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

