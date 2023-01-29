# EXPERIMENT-05
# LU Decomposition 

## AIM:

To write a program to find the LU Decomposition of a matrix.

## EQUIPMENTS REQUIRED :

- Hardware – PCs
- Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHIM :

1.) Import numpy library as np  
2.) Create a matrix using np.array()  
3.) Using scipy.linalg.lu() find L and U, also using scipy.linalg.lu_solve() get the result for LU Decomposition  
4.) Get the output and end the program  
 

## PROGRAM :
### (i) To find the L and U matrix
```python
#Program to find L and U matrix using LU decomposition.
#Developed by: MIDHUN AZHAHU RAJA P
#RegisterNumber: 22008311

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
### (ii) To find the LU Decomposition of a matrix
```python
#Program to solve a matrix using LU decomposition.
#Developed by: MIDHUN AZHAHU RAJA P
#RegisterNumber: 22008311


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x = lu_solve((lu,piv),B)
print(x)

```

## OUTPUT :

###  To find the L and U matrix(OUTPUT) :

![image](https://user-images.githubusercontent.com/118054670/214339197-640a042a-c359-4d22-a900-5a0981874ab7.png)

### To find the LU Decomposition of a matrix(OUTPUT) :

![image](https://user-images.githubusercontent.com/118054670/214339266-2165ac62-d056-44e8-9784-fdf79e6de62b.png)




## RESULT :

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

