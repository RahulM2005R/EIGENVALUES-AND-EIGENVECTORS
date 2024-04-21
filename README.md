# EX-4: EIGENVALUES-AND-EIGENVECTORS
## DATE: 23.03.2024
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Developed by: Rahul M R
#Register Number: 2305003005
import numpy as np
A=np.array([[2,2],[1,3]])
E,EV=np.linalg.eig(A)
print("Eigen values are\n",E,"\nEigen vectors are:\n",EV)
```

## Output:
![image](https://github.com/RahulM2005R/EIGENVALUES-AND-EIGENVECTORS/assets/166299886/62a8034a-3dda-4637-906a-b912d9ad9541)

## Result:
Thus, the Eigenvalue and Eigenvector is successfully solved using python program.
