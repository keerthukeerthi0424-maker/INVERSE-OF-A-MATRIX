# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the NumPy module to use built in function for calculation.
### Step 2: prepare the given matrix and assign it to np.array()
### Step 3: using np.linalg.inv(),we can find the solution.
### Step 4: End the program
## Program:

#Program to find the inverse of a matrix.

#Developed by: Keerthana T A

#RegisterNumber:26009041

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a=np.array([[6,2,3],[3,1,1],[10,3,4]])

b=np.linalg.inv(a)

print(b)

## Output:
<img width="993" height="768" alt="image" src="https://github.com/user-attachments/assets/4605f9ea-6260-4cec-ba8a-d75181d83a87" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

