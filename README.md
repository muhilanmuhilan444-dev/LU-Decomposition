# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: A.MUHILAN
RegisterNumber:25015918 
*/
~~~
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
~~~
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:A.MUHILAN 
RegisterNumber:25015918 
*/
~~~
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
~~~
```

## Output:
<img width="1892" height="904" alt="Screenshot 2025-11-22 211119" src="https://github.com/user-attachments/assets/fd90c0c8-033c-49d4-b221-6364d1c037ba" />
<img width="1873" height="913" alt="Screenshot 2025-11-22 211143" src="https://github.com/user-attachments/assets/ed631b74-0e59-49e0-b656-f3baf8118ce6" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

