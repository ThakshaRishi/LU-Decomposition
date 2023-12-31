# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and lu
2. Get the values for the matrix from the user
3. Find the answer using lu() and assign the answer to variables.
4. Print the output.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Thaksha Rishi
RegisterNumber: 212223100058
*/
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
Developed by: Thaksha Rishi
RegisterNumber: 212223100058
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![Alt text](<Screenshot 2023-12-31 152650.png>)
![Alt text](<Screenshot 2023-12-31 152715.png>)
![Alt text](<Screenshot 2023-12-31 152738.png>)
![Alt text](<Screenshot 2023-12-31 152757.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

