# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : You define a square matrix A.
### Step 2: Check Invertibility
### Step 3: Combine A with the matrix
### Step 4: Perform row operations to transform the left side A

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[2, 1, 1], 
              [1, 1, 1], 
              [1, -1, 2]])
A_inv = np.linalg.inv(A)
print(A_inv)
```
## Output:
<img width="1667" height="767" alt="Screenshot 2026-05-22 103237" src="https://github.com/user-attachments/assets/c5c88a56-8d96-4eb9-81a5-a778a167b625" />
<img width="1878" height="905" alt="Screenshot 2026-05-22 103247" src="https://github.com/user-attachments/assets/e691c415-b3a8-463f-b7f6-579492cc911f" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

