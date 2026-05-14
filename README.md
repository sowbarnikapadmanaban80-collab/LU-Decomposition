# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy modules as np
2. Define the matrix as numpy array.
3. Using the np.linalg.inv(), we can find the inverse of the given matrix.
4. Display the result using print() function

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SOWBARNIKA M P
RegisterNumber: 212225230271
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SOWBARNIKA M P
RegisterNumber: 212225230271
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
Solution=lu_solve(XMatrix,BMatrix)
print(Solution)
*/
```

## Output:

(i) <img width="1227" height="482" alt="Screenshot 2026-05-14 184841" src="https://github.com/user-attachments/assets/bf435718-0ec2-4b1b-add0-dfd75b30967d" />

(ii) <img width="1216" height="200" alt="Screenshot 2026-05-14 184859" src="https://github.com/user-attachments/assets/ae100b44-636a-4c2d-935a-a1d5b48adaf8" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

