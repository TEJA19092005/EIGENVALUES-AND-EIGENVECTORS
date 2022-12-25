# EIGENVALUES-AND-EIGENVECTORS
## AIM:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
### Step1 : 
Import numpy as np
### Step 2:
Assign np.array() in eigen values and eigen vectors 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both values and vectors,then end the program.
## PROGRAM:
```PYTHON
#Program to find the eigen values and eigen vectors.
#Developed by: tejaswini
#RegisterNumber:22004187
import numpy as np
a=np.array([[4,2],[2,4]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```
## OUTPUT:
![OUTPUT](R4.png)
## RESULT:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
