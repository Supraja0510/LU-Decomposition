# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
Step1:
Define the package as scipy.linalg import lu.
Step2:
Get input from user and print L and U matrix by 'print' .
Step3:
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.  
Step4:
Print the variable 'X'
```

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Supraja B
RegisterNumber: 2305002026

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Supraja B
RegisterNumber: 2305002026

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/Supraja0510/LU-Decomposition/assets/155217478/04858f78-dcd1-480f-bc0c-eee4167f18b1)
![image](https://github.com/Supraja0510/LU-Decomposition/assets/155217478/025f8d40-1613-43e7-a8b3-a7f1de6ac573)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

