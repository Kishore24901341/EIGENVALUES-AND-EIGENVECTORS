## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import numpy which has built-in function for matrix operation
### Step 2:
Represent the matrix as a 2D numpy array
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
import numpy as np

matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)


## Output:
![image](https://github.com/user-attachments/assets/4adad225-15b5-477d-811c-cfad26d04dce)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
