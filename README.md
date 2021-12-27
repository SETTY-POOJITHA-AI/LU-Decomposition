# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Assign the values.
3. Using scipy.linalg,we get two results(first is L matrix and second is U matrix)of the given matrix.
4. End the program.

## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Poojithasetty
RegisterNumber: 21003760
import numpy as np
import numpy as np
import scipy
from scipy.linalg import lu
A =eval(input())
P,L,U=lu(A)
print(L)
print(U)
--------------------------------------------------


import numpy as np
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
![LU decomposition](ludecomposition1output.PNG)
![LU decomposition](ludecomposition2output.PNG)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

