# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the build-in functions for calculation.
### Step 2: Prepare the lists from each equation and assign in np.array.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program.
## Program:
#Program to find the rank of a matrix.
#Developed by: R.MAHALAKSHMI
#RegisterNumber:212223230117

import numpy as np
# Define the matrix
matrix = np.array([[5, -3, -10], [2, 2, -3], [-3, -1, 5]])
# Calculate the rank of the matrix
rank = np.linalg.matrix_rank(matrix)
# Print the rank
print(rank)
## Output:
![image](https://github.com/Maharavi2006/RANK-OF-A-MATRIX/assets/154535981/0232c437-ba13-40d2-a865-83ef8214d995)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

