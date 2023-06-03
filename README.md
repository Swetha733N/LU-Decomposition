# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.

2. From scipy package import lu().

3.Get input from user and pass it as an array.

4. Get P, L, U matrix using lu()
 
5.Print L and U matrix

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: SWETHA N
RegisterNumber: 212222110050

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: SWETHA N
RegisterNumber: 212222110050

import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:
(i) To find the L and U matrix
![image](https://github.com/Swetha733N/LU-Decomposition/assets/122199934/1c831ce8-ab12-4e2d-92ea-e800351a913c)


(ii) To find the LU Decomposition of a matrix
![image](https://github.com/Swetha733N/LU-Decomposition/assets/122199934/8e8a986e-b53b-4c2d-8c30-d5dce4a8f436)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

