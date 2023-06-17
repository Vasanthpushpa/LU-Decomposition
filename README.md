# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.  Import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L, U matrix using lu()
5. Print L and U

## Program:
```
(i) To find the L and U matrix

Program to find L and U matrix using LU decomposition.
Developed by: VASANTH P
RegisterNumber: 212222240113

import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix

Program to solve a matrix using LU decomposition.
Developed by: VASANTH P
RegisterNumber: 21222224113


import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(a)
x = lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/Vasanthpushpa/LU-Decomposition/assets/119291100/d93dc2a2-25c7-4886-bb56-e49b89b62b3b)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/Vasanthpushpa/LU-Decomposition/assets/119291100/e825d6b5-1259-4710-b6fa-e7c517ceb3dc)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

