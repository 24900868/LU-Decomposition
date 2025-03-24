# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
Step 1: import numpy as np
Step 2: from scipy package import lu
Step 3: get input from the user
Step 4: print result
```

## Program:
(i) To find the L and U matrix
Program to find the L and U matrix.
```
Developed by: M.Mahalakshmi 
RegisterNumber: 212224230148

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
Program to find the LU Decomposition of a matrix.
```
Developed by: M.Mahalakshmi
RegisterNumber: 212224230148

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)
```

## Output:
(i)

![Screenshot 2025-03-24 081912](https://github.com/user-attachments/assets/65761201-bced-4cb2-a679-809d7501f67f)

(ii)

![Screenshot 2025-03-24 081928](https://github.com/user-attachments/assets/aa0511a7-e810-4beb-bf8d-e52a8fb56e3f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

