# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import libraries
2. Get the matrix from the user
3. Find the L and U 
4. print the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JYESVANTHE V
RegisterNumber:23013991
'''Program to find L and U matrix using LU decomposition.
Developed by: JYESVANTHE V
RegisterNumber: 23013991
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: JYESVANTHE V
RegisterNumber: 23013991
'''Program to solve a matrix using LU decomposition.
Developed by: JYESVANTHE V
RegisterNumber: 23013991
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```

## Output:
![Alt text](<Screenshot 2023-12-13 082024.png>)
![Alt text](<Screenshot 2023-12-13 082041.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

