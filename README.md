# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: ANDREW VARGHESE VS
RegisterNumber: 23013668'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition]()
<img width="829" alt="Screenshot 2023-10-07 at 7 13 26 PM" src="https://github.com/Andrewvarghese653/LU-Decomposition/assets/145822115/093f8832-7459-4657-93a4-af370d7a3560">
<img width="743" alt="Screenshot 2023-10-07 at 7 14 03 PM 2" src="https://github.com/Andrewvarghese653/LU-Decomposition/assets/145822115/00a5b8aa-2f62-49bc-8e33-68effce73aef">




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

