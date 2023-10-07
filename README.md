# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
arrange the given matrix in np.array command 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
run the program and get the output

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: G Harish
#RegisterNumber: 23000630
import numpy as np
a = np.array([[4,2],[2,4]])
b,c = np.linalg.eig(a)
print("Eigen values are",b,end="")
print(" and Eigen Vectors are",c)
```

## Output:

![Screenshot 2023-10-07 190504](https://github.com/Harish2404lll/EIGENVALUES-AND-EIGENVECTORS/assets/141472096/d6572519-4bc1-4e47-8e6f-7800b75a3a72)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
