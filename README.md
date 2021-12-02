# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : get the matrix from the user
### Step 2: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 3: print the two results(Eigen values and Eigen vectors)
### Step 4: end the program

## Program:
~~~
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
~~~
## Output:
![github logo](eigenvalue.png)
![github logo](eigenvector.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
