# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the NumPy library as np and the lu function from the scipy.linalg module for LU decomposition.
2. Take matrix input from the user using input() and convert it into a NumPy array using np.array(eval(input())).
3. Use the lu() function to decompose the matrix A into three matrices:

    P: Permutation matrix

    L: Lower triangular matrix

    U: Upper triangular matrix
4. Print the L (Lower triangular) and U (Upper triangular) matrices using print(L) and print(U).

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: POTHU SUMANTH
RegisterNumber: 212224240115
*/
```
    import numpy as np
    from scipy.linalg import lu
    A = np.array(eval(input()))
    P,L,U=lu(A)
    print(L)
    print(U)
```
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```
    import numpy as np
    from scipy.linalg import lu_factor,lu_solve
    A=np.array(eval(input()))
    b=np.array(eval(input()))
    lu,piv=lu_factor(A)
    X = lu_solve((lu,piv),b)
    print(X)
```
```

## Output:

<img width="1060" height="351" alt="Screenshot 2025-10-16 151210" src="https://github.com/user-attachments/assets/01f4afd6-73f2-435a-98cb-88beca1fdb49" />

<img width="779" height="165" alt="Screenshot 2025-10-16 151305" src="https://github.com/user-attachments/assets/253d940d-b79b-4089-bd00-370363e77fea" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

