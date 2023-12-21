# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy module and scipy linalg module to use the built in function for calculation
2. prepare the list from each linear equaction  and assign in numpy.array()
3. perform scipy linlag.lu() to find the pivot table,lower triangle and upper triangle matrix
4. end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: selva kumar R.
RegisterNumber: 23012861
from scipy.linalg import lu
import numpy as np
arr=eval(input())
a=np.array(arr)
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: selva kumar R.
RegisterNumber: 23012861
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)

*/
```

## Output1:
![Screenshot 2023-12-21 210023](https://github.com/GANESH23012861/LU-Decomposition/assets/147139861/fc8e978d-1636-4c00-8f48-bfff5587b88f)

## Output2:
![Screenshot 2023-12-21 210043](https://github.com/GANESH23012861/LU-Decomposition/assets/147139861/15ad45b7-cd9b-47dd-9d6c-5db3a566910a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
