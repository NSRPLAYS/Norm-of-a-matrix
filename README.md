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
# Register No:24009928
# Developed By:NAVEEN SAIRAM B
# 1-Norm of a Matrix
import numpy as np
inputarray=np.array(eval(input()))
onenorm=np.linalg.norm(inputarray,1)
print(onenorm)



# 2-Norm of a Matrix
import numpy as np
inputarray=np.array(eval(input()))
twonorm=np.linalg.norm(inputarray,2)
print(f"{twonorm:.2f}")



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
infinty=np.linalg.norm(a,np.inf)
print(infinty)



```
## Output:
### 1-Norm of a Matrix
![one norm](image.png)

### 2-Norm of a Matrix
![two norm](image-1.png)

### Infinity Norm of a Matrix
![inf norm](image-2.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
