# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. From Scipy package import lu
3. Get input from the user
4. Print result

## Program:
```
Program to find L and U matrix using LU decomposition.
Developed by: Sriram S
RegisterNumber:22009336

import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
```
Program to solve a matrix using LU decomposition.
Developed by: Sriram S
RegisterNumber:22009336

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
 
```

## Output:
### 1st Problem
![lu1](https://user-images.githubusercontent.com/119094390/213908002-c7c18cdd-a33a-4642-96f6-2bf41e870e9c.png)


### 2nd Problem
![lu2](https://user-images.githubusercontent.com/119094390/213908021-38d9a126-1e53-4e9c-9960-08bc82a23e0d.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

