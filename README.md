# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' . 
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X' 
```

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:RAGUNATH R
RegisterNumber:212222240081
import numpy as np
from scipy.linalg import lu

arr=eval(input())
P,L,U=lu(arr)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:RAGUNATH R 
RegisterNumber:212222240081
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve

arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])

LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)

print(res)


*/
```

## Output:
(i) To find the L and U matrix

![image](https://user-images.githubusercontent.com/113915622/236655343-2d7a8ed4-c562-414a-8853-00072eeb7381.png)

(ii) To find the LU Decomposition of a matrix

![image](https://user-images.githubusercontent.com/113915622/236655280-44514f6f-b4c2-41e1-9440-e8884596904f.png)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

