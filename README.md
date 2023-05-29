# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# Step 1:
Import numpy library using import statement.

# Step 2:
From scipy package import lu().

# Step 3:
Get input from user and pass it as an array.

# Step 4:
Get P, L, U matrix using lu()

# Step 5:
Print L and U matrix

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: JAYASRI DODDA
RegisterNumber: 212222240028
'''
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: JAYASRI DODDA
RegisterNumber: 212222240028
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = eval(input())
b = eval(input())
lu , piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) ![Screenshot 2023-05-29 at 16-39-27 Ex05-CR- LU Decomposition Attempt review](https://github.com/jayasridodda/LU-Decomposition/assets/123259278/9afacee3-dbed-4de5-b0e7-ba2d5cbed554)
(ii)![Screenshot 2023-05-29 at 16-39-05 Ex05-CR- LU Decomposition Attempt review](https://github.com/jayasridodda/LU-Decomposition/assets/123259278/4e906d4f-c81c-4d54-9a50-8861bf71d945)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

