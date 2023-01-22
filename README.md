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
 Step 3: Using the np.linalg.eigen()
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
![image](https://user-images.githubusercontent.com/118708624/213919422-1571a098-1587-4510-920a-28e87988b215.png)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
