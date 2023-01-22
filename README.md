# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : To find inverse of a matrix using python programming
### Step 2: Import numpy as np
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:Print result 

## Program:
```
name:sirisha onteddu
ref.no:22003264
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://user-images.githubusercontent.com/119389139/213916437-8e067f8e-8cd9-400e-87b1-f00b86d882ee.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
