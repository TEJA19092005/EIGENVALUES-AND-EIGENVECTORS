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
#Developed by: M THEJESWARAN
#RegisterNumber: 212223240168

import numpy as np
a=np.array([[4,2],[2,4]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```
## OUTPUT:
<img width="616" alt="image" src="https://user-images.githubusercontent.com/121222763/214516669-da8c1594-e133-4137-a548-9b22e877e6d8.png">

## RESULT:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
