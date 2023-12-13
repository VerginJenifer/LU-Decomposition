# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# Step 1:
Import the numpy module to use the built-in functions for
calculation
# Step 2:
Prepare the lists from each linear equations and assign in
np.array()
# Step 3:
Using the scipy.linalg, we can find the solutions
# Step 4:
End the program
## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: D Vergin Jenifer
#RegisterNumber: 23004210
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
P,L, U = lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: D Vergin Jenifer
RegisterNumber: 23004210
'''

# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![Screenshot 2023-12-13 111306](https://github.com/VerginJenifer/LU-Decomposition/assets/136251012/253db0df-c863-45bf-acde-9b191c55420b)

![image](https://github.com/VerginJenifer/LU-Decomposition/assets/136251012/35d2ca9e-2dec-4f66-9a15-5fc59658b64f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

