# Norm-of-a-matrix

## Aim 
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipments Required 
 1. Hardware – PCs
 2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for 1-Norm of a Matrix
 1. Get the input matrix using np.array()
 2. Find the 1-norm of the matrix using np.linalg.norm(matrix, 1)
 3. Print the 1-norm of the matrix in two decimal places
 
## Algorithm for 2-Norm of a Matrix
 1. Get the input matrix using np.array()
 2. Find the 2-norm of the matrix using np.linalg.norm(matrix, 2)
 3. Print the 2-norm of the matrix in two decimal places

## Algorithm for Infinity Norm of a Matrix
 1. Get the input matrix using np.array()
 2. Find the Infinity norm of the matrix using np.linalg.norm(matrix, np.inf)
 3. Print the Infinity norm of the matrix in two decimal places

## Program 
~~~
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: ANISE KINSELLA A
RegisterNumber: 212225040021
''' 
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array(eval(input()))
results = np.linalg.norm(matrix,1)
print(round(results,2))




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: ANISE KINSELLA A
RegisterNumber: 212225040021
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,2)
print(round(result,2)) 




# Infinity Norm of a Matrix
'''
Program to find infinity of a matrix.
Developed by: ANISE KINSELLA A
RegisterNumber: 212225040021
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,np.inf)
print(round(result,2))

~~~

## Output 
1-Norm of a Matrix
<img width="1413" height="677" alt="image" src="https://github.com/user-attachments/assets/86a8c22b-748f-44d4-90a3-992a178d4b03" />
<img width="1277" height="370" alt="image" src="https://github.com/user-attachments/assets/272b2e3b-54f1-4e1b-a0e5-71fe8955cbbf" />


2-Norm of a Matrix
<img width="1437" height="722" alt="image" src="https://github.com/user-attachments/assets/a5abefa5-86e1-4eea-832c-6c6ed3858ca7" />
<img width="1271" height="568" alt="image" src="https://github.com/user-attachments/assets/ab38c178-2358-45d8-a54d-6cf55f2f210d" />

Infinity Norm of a Matrix
<img width="1422" height="658" alt="image" src="https://github.com/user-attachments/assets/d840f6ea-e614-4b6a-bebe-6f199c46482b" />
<img width="1280" height="435" alt="image" src="https://github.com/user-attachments/assets/ca182dd8-8669-4014-ae27-8b87838ec576" />


## Result 
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
