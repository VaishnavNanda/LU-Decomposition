# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: A.Thiyagarajan
#RegisterNumber: 212222240110
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: A.Thiyagarajan
RegisterNumber: 212222240110
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:


### (i) To find the L and U matrix:

![l1](/l1.png)


### (ii) To find the LU Decomposition of a matrix:


![l2](/l2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

