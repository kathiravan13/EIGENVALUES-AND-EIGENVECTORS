# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import num py
### Step 2: use an array function
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: then print the eigen value

## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
evalues,evector=np.linalg.eig(a)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evector
```

## Output:

![Screenshot from 2023-04-07 17-25-10](https://user-images.githubusercontent.com/119831303/230604848-29794236-cab8-43d1-94de-c8fb735ca17c.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
