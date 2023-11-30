# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Convert the matrix to row-echelon form
### Step 2: Count the number of non-zero rows in row-echelon form
### Step 3: Output the rank of the matrix
### Step 4: Return the rank
## Program:
```
import numpy as np
A=np.array([[[1,2,3],[3,6,9],[3,3,6]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![IMAGE]( https://raw.githubusercontent.com/Girithickrohan/RANK-OF-A-MATRIX/main/Screenshot%202023-11-30%20100355.png)
![IMAGE](https://raw.githubusercontent.com/Girithickrohan/RANK-OF-A-MATRIX/main/Screenshot%202023-11-30%20100317.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

