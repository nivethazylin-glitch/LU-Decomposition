# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## 5a
1. import the NumPy and SciPy libraries
2. Define the input matrix A
3. Perform LU decomposition to obtain P,L, and U
4. print the L and U matrices
## 5b
1. import the NumPy library and required SciPy functions
2. 2,get the coefficient matrix A and the constant matrix B as input
3. perform LU factorization and solve the equations to obtain X
4. print the solution matrix X

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
 Developed by: Nivetha.T
 RegisterNumber:26005007 
 '''
 import os
 os.environ["OPENBLAS_NUM_THREADS"]="1"
 import NumPy as np
 from SciPy.linalg import lu
 A=np.array(eval(input()))
 P,L,U=lu(A)
 print(L)
 print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
 Program to find the LU Decomposition of a matrix.
 Developed by: Nivetha.T
 RegisterNumber: 26005007
 */
 import os
 os.environ["OPENBLAS_NUM_THREADS"]="1"
 import numpy as np
 from scipy.linalg import lu_factor,lu_solve
 a=np.array(eval(input()))
 b=np.array(eval(input()))
 l,p=lu_factor(a)
 x=lu_solve((l,p),b)
 print(x)
```

## Output:
![lu decomposition]()
## 5a
<img width="1907" height="1026" alt="image" src="https://github.com/user-attachments/assets/cc46f6a8-f92e-468b-9b6b-bc6ffe2aa4d7" />
## 5b
<img width="1902" height="1010" alt="image" src="https://github.com/user-attachments/assets/0125bf99-ff6f-439a-8c9d-e1b143c672ea" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

