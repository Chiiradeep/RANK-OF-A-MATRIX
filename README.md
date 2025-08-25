# RANK OF A MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each linear equations and assign in np.array()

Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4: End the program
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: Chiiradeep R
#RegisterNumber: 212224240028

import numpy as np
def find_rank(matrix):
    return np.linalg.matrix_rank(matrix)
    
matrix = [[1,2,3],[3,6,9]]
rank = find_rank(matrix)
print(rank)
~~~
## Output:
<img width="776" height="613" alt="image" src="https://github.com/user-attachments/assets/a20e9ab1-2d43-44fa-b07d-cc3190daa60b" />

<img width="1407" height="279" alt="Screenshot 2025-08-18 110945" src="https://github.com/user-attachments/assets/6fd052ef-4db4-47da-a993-895a7f1660f8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

