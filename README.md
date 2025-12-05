# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import numpy module to us ethe built-in functions for calculation
### Step 2:
repare the lists from each linear equarions and assign in np.array
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Dhruv.D
#RegisterNumber:24900416
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
result1,result2=np.linalg.eig(A)
print(f"Eigen values are {result1} and Eigen Vectors are {result2}")
```
## Output:

![alt text](<ex 4.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
