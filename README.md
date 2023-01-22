# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import the numpy module to use the built-in functions for calculation
## Step 2:
Prepare the lists from each linear equations and assign in np.array()
## Step 3:
Using the np.linalg.solve(), we can find the solutions.
## Step 4:
End the program
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: GOKUL.S
RegisterNumber: 22008488
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: GOKUL
RegisterNumber: 22008488
*/
'''Program to solve a matrix using LU decomposition.
Developed by: Gokul
RegisterNumber: 22008488
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![lu decomposition]()
![Screenshot (151)](https://user-images.githubusercontent.com/121148715/213900474-b0c3b85f-e8a0-41b7-94a7-ac2e29281772.png)

![Screenshot (152)](https://user-images.githubusercontent.com/121148715/213900475-3a5b92af-219b-4b89-b021-7d4dd6116642.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

