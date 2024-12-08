# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :

import the numpy module to use the built-in-function for calculation

### Step 2: 

pepare the lists for the given matrix and assign in np.array()

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

End the program

## Program:

```python
#Program to find the eigen values and eigen vectors.
#Developed by:S.Nandhini 
#RegisterNumber:24013591
import numpy as np
a=np.array([[2,2],[1,3]])
eigen_value,eigen_vectors=np.linalg.eig(a)
print(f"Eigen values are {eigen_value} and Eigen Vectors are {eigen_vectors}")
```

## Output:

![alt text](<Screenshot 2024-12-08 173650.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
