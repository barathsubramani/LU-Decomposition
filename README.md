# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and lu, lu_factor, lu_solve (from scipy.linalg)
2. Assign the values to the arrays created
3. Find the L and U matrix using p,l,u = lu(variable), lu_factor(variable), lu_solve(variable)
4. Print the values

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Barath S
RegisterNumber: 22008643
*/
```
```python
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
p,l,u = lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Barath S
RegisterNumber: 22008643
*/
```
``` python
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(a)
x = lu_solve((lu, piv), b)
print(x)
```

## Output:
To find the L and U matrix
![model](out.png)
To find the LU Decomposition of a matrix
![model](put.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

