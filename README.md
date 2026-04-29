# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
#Program to find the rank of a matrix.

#Developed by: B ARPUTHA

#RegisterNumber:212225040028

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

matrixA=np.array([[3,2,5],[1,1,2],[3,3,6]])

rank=np.linalg.matrix_rank(matrixA)

print(rank) 
## Output:
<img width="258" height="111" alt="image" src="https://github.com/user-attachments/assets/70b80e0f-9d14-4da2-a6f3-ceb9419f1599" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

