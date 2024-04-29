# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'

 

## Program:
(i) To find the L and U matrix
```
##Program to find L and U matrix using LU decomposition.

##Developed by: R.sivakumar

##RegisterNumber: 23013501

import numpy as np

from scipy.linalg import lu

a=np.array(eval(input()))

p,L,u=lu(a)

print(L)

print(u)
```

## Output:
<img width="578" alt="Screenshot 2024-04-06 133315" src="https://github.com/SIVAmech123/LU-Decomposition/assets/151629067/1e1fc889-f206-4f1c-8711-0d9396b3497b">

<img width="626" alt="Screenshot 2024-04-06 133332" src="https://github.com/SIVAmech123/LU-Decomposition/assets/151629067/9c6ef281-93e8-4730-88e2-bd3ec48ced73">

![Screenshot 2024-04-29 194726](https://github.com/SIVAmech123/LU-Decomposition/assets/151629067/90036b5e-74f5-4bbf-95b2-8246a4c0f709)

![Screenshot 2024-04-29 194733](https://github.com/SIVAmech123/LU-Decomposition/assets/151629067/4832e502-404c-45c1-9928-7a3a8a0b0c40)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

