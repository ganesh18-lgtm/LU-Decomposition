# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find the L and U matrix.
Developed by: Ganesh B C
RegisterNumber: 212225040090'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

'''Program to find the LU Decomposition of a matrix.
Developed by: Ganesh B C
RegisterNumber: 212225040090'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X) 
```

## Output:
(i).
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f070c2f9-013d-455b-98b6-b8bc952eb760" />
(ii).
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e2021a69-25a2-4919-aa6d-e780a96f80aa" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

