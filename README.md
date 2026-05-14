# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.inv(), we can find the solutions.
### Step 4: End the program

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result=np.linalg.inv(A)
print(result)
```
## Output:
<img width="1295" height="941" alt="Screenshot 2026-05-14 185554" src="https://github.com/user-attachments/assets/a994ef5f-88fb-4891-83cc-63b75e44b432" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

