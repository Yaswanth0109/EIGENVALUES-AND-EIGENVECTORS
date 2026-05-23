# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: YASWANTH V
#RegisterNumber:25010248
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0, 0, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1429" height="781" alt="image" src="https://github.com/user-attachments/assets/5eff03ab-2482-464b-bc57-c2d5fed53fd2" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
