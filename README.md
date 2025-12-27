# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
step 1 : Import the NumPy library to perform matrix and linear algebra operations.
step 2 : Define the matrix using np.array() with the given values.
step 3 : Compute eigenvalues and eigenvectors using the np.linalg.eig() function.
step 4 : Display the results, where eigenvalues represent the characteristic values of the matrix and eigenvectors represent the corresponding directions.


## Program:
```py
import numpy as np
a=np.array([[-2,2,-3],
           [2,1,-6],
           [-1,-2,0]])
eigenvalues, eigenvectors=np.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)

```
## Output:
<img width="1497" height="883" alt="image" src="https://github.com/user-attachments/assets/cd3d1fbc-b317-46cc-abfa-4c5bb411b1b7" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
