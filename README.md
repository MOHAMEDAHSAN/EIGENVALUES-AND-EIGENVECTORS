# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy module as np
### Step 2: 
Using np.array() create the required matrix
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the created matrix.
### Step 4: 
Display the obtained Eigen Values and Eigen Vectors using print()
## Program:
~~~Python
#Program to find the eigen values and eigen vectors.
#Developed by: S MOHAMED AHSAN
#RegisterNumber: 23001044
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues,evectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(evalues,evectors))
~~~
## Output:
![eig](/eig.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
