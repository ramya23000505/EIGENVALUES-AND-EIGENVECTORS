# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Ramya R
#RegisterNumber: 212223230169
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigvalues,eigvectors=np.linalg.eig(matrix)
print("Eigen values are",eigvalues,"and Eigen Vectors are",eigvectors)
```
## Output:
![Screenshot 2024-04-14 190910](https://github.com/ramya23000505/EIGENVALUES-AND-EIGENVECTORS/assets/149370791/caef6fb7-f65e-431b-83f8-c7fc09fb9f30)
![Screenshot 2024-04-14 190941](https://github.com/ramya23000505/EIGENVALUES-AND-EIGENVECTORS/assets/149370791/531b923d-3e67-4fa3-81a9-a7302b10c3b7)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
