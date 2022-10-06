# Multiplying-two-matrix

## AIM:
write a python program to multiply-two-matrix to display the product of the two array.
## ALGORITHM:

### Step 1:
import numpy 
### Step 2:
Get value from the user
### Step 3:
Create two empty list
### Step 4:
Append the value in empty list 
### Step 5:
Multiply two array and display the output.
### step6:
End the program.

## PROGRAM:
```python
import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
p1 = np.array(l1)
p2 = np.array(l2)
p3 = p1*p2
print("Product of two arrays is:",p3) 
```
## OUTPUT:
![output](/twomatrix.png)
## RESULT:
Thus the product of two matrix is obtained by using
python program.