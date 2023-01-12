# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy
### Step 2: solve np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
'''
#Program to find the eigen values and eigen vectors.
#Developed by: Archana.k
#RegisterNumber: 22009150
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
'''
## Output:
![Screenshot 2023-01-12 at 14-24-47 Exp 04 - Eigen values and Eigen vectors Attempt review](https://user-images.githubusercontent.com/118708624/212022632-579a536e-ecf9-4e5c-84d5-7a3b7236b1c8.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
