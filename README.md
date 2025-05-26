# EIGENVALUES-AND-EIGENVECTORS
## NAME: Jayagar.T
## REG.NO: 212224220042
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations
### Step 2: 
Prepare the lists from each linear equations ans assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program

## Program:
```
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/a0dc6dc8-89a8-48ef-a2e2-15049bd0c9da)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
