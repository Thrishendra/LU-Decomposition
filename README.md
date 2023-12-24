# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. first use import statment
2. second use the numpy oparator
3. third use the print statment
4. i got the output

## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: T.Thrishendra
RegisterNumber: 23003501
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
a=np.array(arr)
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: T.Thrishendra
RegisterNumber:23003501 
'''

# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)
```

## Output:
![Screenshot 2023-12-24 200825](https://github.com/Thrishendra/LU-Decomposition/assets/145742464/668e16d0-4fdb-4298-aeb5-5c7a8e65ad32)

![Screenshot 2023-12-24 200849](https://github.com/Thrishendra/LU-Decomposition/assets/145742464/99f28b90-4bd9-489b-82cc-1fd3fe3d393f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

