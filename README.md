# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Dhineshkumar.L
#RegisterNumber:212224230066
import numpy as np
A=np.array([[2,2],[1,3]])
eig_values,eig_vectors=np.linalg.eig(A)
print(f"Eigen values are {eig_values} and Eigen Vectors are {eig_vectors}")
```

## Output:
![alt text](<Screenshot 2025-04-11 100724.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
