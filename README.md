# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpr module.
### Step 2: Declare the matrix to a variable.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the Eigen values and Vectors. And End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Athul Krishna A V
#RegisterNumber: 25013602

import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
<img width="1254" height="856" alt="image" src="https://github.com/user-attachments/assets/d341c7b2-eb7c-4678-aeee-6291efae160e" />

## Output:
<img width="1250" height="214" alt="image" src="https://github.com/user-attachments/assets/c4e7375f-561d-42c5-96b9-88156fcbfbcf" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
