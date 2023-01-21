# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
```
 Step1 : import numpy
 Step 2: solve np.array()
 Step 3: Using the np.linalg.eigen(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
 Step 4: End the program
```
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Archana.k
#RegisterNumber: 22009150
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot (26)](https://user-images.githubusercontent.com/118708624/213873304-aee95d4b-a78a-4c15-858d-c2b1fb24acc3.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
