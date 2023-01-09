# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the elements of augmented matrix into arrays a and b

2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution

5.Find X by solving UX = V by backward substitution

6.Print Array X as the solution


## Program:
(i) To find the L and U matrix
```py
Program to find L and U matrix using LU decomposition.
Developed by:K.Nagul 
RegisterNumber: 22008933

import numpy as np
from scipy.linalg import lu
arr = eval(input())
A = np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```py
Program to solve a matrix using LU decomposition.
Developed by: K.Nagul
RegisterNumber: 22008933


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![lu decomposition](/lu1.png)
![output](/lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

