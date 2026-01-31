# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the necessary numerical library (numpy) to access high-level linear algebra functions.
### Step 2: Input the data by creating a 2D array or list representing the matrix $A$.
### Step 3: Pass the matrix into the linalg.matrix_rank() function, which calculates the number of linearly independent rows or columns. 
### Step 4: Store the calculated value in a variable and print it to the console.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: Mohana Priya D
#RegisterNumber: 212225230182
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
## Output:
<img width="955" height="743" alt="Screenshot 2026-01-31 124150" src="https://github.com/user-attachments/assets/adf44178-451a-423c-a202-dfaec127f5bd" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

