# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy module to use built-in functions for calculations
### Step 2: 
prepare the lists of values from the given matrix and convert it into an array using np.array()
### Step 3: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the Eigenvalues and Eigenvectors and end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Ashqar Ahamed S.T
#RegisterNumber: 212224240018
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vector}")
```

## Output:
<img width="1317" height="903" alt="Exp4" src="https://github.com/user-attachments/assets/59369130-aad0-4b36-8e9c-6cbe12b1752c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
