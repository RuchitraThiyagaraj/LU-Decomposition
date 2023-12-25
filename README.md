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
'''Program to find L and U matrix using LU decomposition.
Developed by: RUCHITRA THIYAGARAJ
RegisterNumber: 23000100
'''
from scipy.linalg import lu
import numpy as np 
arr=eval(input())
a=np.array(arr)
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: RUCHITRA THIYAGARAJ
RegisterNumber: 23000100
'''
# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
const=eval(input())
a=np.array(arr)
b=np.array(const)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)
```

## Output:
![image](https://github.com/RuchitraThiyagaraj/LU-Decomposition/assets/154776996/8c6b9c34-5efe-49fa-b622-a4367d6079c1)
</br>
</br>
![image](https://github.com/RuchitraThiyagaraj/LU-Decomposition/assets/154776996/df090995-8ad9-4b8b-b824-807fd68292fd)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

