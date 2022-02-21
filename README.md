# Inverse-of-matrix

## AIM:
To write a python program for Inverse of matrix
## ALGORITHM:
Step 1:
Get the input from the user

Step 2:
Use append() to add new elements in the list

Step 3:
Get the input from the user using np.array()

Step 4:
Inverse = np.linalg.inv() to inverse the matrix and print the output

Step 5:
End the program
## PROGRAM:
```
Developed by: sarvesh
RegisterNumber : 21000082
import numpy as np
l1, l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)   
value1= np.array(l2)
inverse = np.linalg.inv(value1)
print(inverse)
```
## OUTPUT:
![git log](p1.png)
## RESULT:
Thus the inverse of given matrix is successfully solved using python program