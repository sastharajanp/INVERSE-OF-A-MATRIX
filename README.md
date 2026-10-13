# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import os and Import the numpy module to use the built-in functions for calculation respectively
### Step 2: Prepare the lists from the given matrix and assign in a = np.array()
### Step 3: Using the b = np.linalg.inv(a)
### Step 4: Find the solution using print(b)

## Program:
#Developed by: SASTHARAJAN P
#RegisterNumber: 26009606

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

a = np.array([[1, 0, 3] , [-1, 2, -2] , [2, 3, -1]])
b = np.linalg.inv(a)

print(b)

## Output: <img width="1292" height="812" alt="image" src="https://github.com/user-attachments/assets/13fbd1a3-f3f6-4c43-bcce-b2498675990b" /> 
<img width="1257" height="227" alt="image" src="https://github.com/user-attachments/assets/97c4cd34-a75d-4143-914d-5f5ff9e819e6" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

