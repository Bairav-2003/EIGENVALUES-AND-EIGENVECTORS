# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : start
### Step 2: enter a value in a
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:stop 

## Program:
~~~ python
#Program to find the eigen values and eigen vectors.
#Developed by: bairav skanda loha
#RegisterNumber:21000106
import numpy as np
a = np.array([[2,2],[1,3]])
values,vector = np.linalg.eig(a)
print("Eigen values are {0} and Eigen Vectors are {1}".format(values,vector))
~~~


## Output:
![output](eigen.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
