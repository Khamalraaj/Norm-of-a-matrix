# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix

```
Developed by: Khamalraaj .S
RegisterNumber: 212224230122
```
```
# 1-norm of a matrix.
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,1)
print("{:.2f}".format(ans))
```
```
# 2-Norm of a Matrix
import numpy as np
a= np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))
```


```
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))
```
## Output:

### 1-Norm of a Matrix
![Screenshot 2025-04-21 225633](https://github.com/user-attachments/assets/12730125-40ae-4e8c-b122-9260712c86f8)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2025-04-21 225645](https://github.com/user-attachments/assets/fa5b4c1a-f95f-46d2-90af-ffb1feff8230)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2025-04-21 225645](https://github.com/user-attachments/assets/cb4dfe54-6dc1-4067-a293-c4ce67bd1bb4)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
