# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. import scipy.linalg import lu
3. get an input  
4. print L and print U

## Program:
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: Aadheeshwar.A 
RegisterNumber: 21001368
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)
*/
```
## Output:
![Github logo](Capture.PNG)


## Result:
Thus the program to find the L and U matrix using LU Decomposition  is written and verified using python programming.

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. import scipy.linalg import lu
3. get an input  
4. print L and print U

## Program:
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)
*/
```
## Output:
![Github logo](lu.PNG)


## Result:
Thus the Program to solve a matrix using LU decomposition  is written and verified using python programming.


