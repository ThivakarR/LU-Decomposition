# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy package as np

2.From scipy package import lu

3.Get input from the user

4.Print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
'''

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
![lu decomposition]()
![Screenshot 2023-06-11 163211](https://github.com/ThivakarR/LU-Decomposition/assets/118707074/2a64c025-7bb3-4615-81b2-d9fbcd8debd1)

![Screenshot 2023-06-11 163336](https://github.com/ThivakarR/LU-Decomposition/assets/118707074/87948a48-80a8-4e2f-b509-e735659eb708)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

