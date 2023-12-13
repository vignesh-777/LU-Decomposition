# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start a program.
2. Import scipy.linalg and numpy.
3. Get input from user and store in array and print L.
4. Using L find the U of the matrix and later fing LU of the matrix
End the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Vignesh R
RegisterNumber: 23005542'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: vignesh R
RegisterNumber: 23005542
'''
# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor ,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![lu decomposition](/lu_1.png)
![](/lu_2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

