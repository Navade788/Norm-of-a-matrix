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
```
 Register No: 212224230180
 Developed By: S.Navadeep
```
```Python
# 1-Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)

# 2-Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))

# Infinity Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))
```

## Output:
### 1-Norm of a Matrix

![WhatsApp Image 2025-05-13 at 13 56 43_d5e642f6](https://github.com/user-attachments/assets/5c5191fb-8ef6-40f8-ada8-1030cd51e903)

### 2-Norm of a Matrix

![WhatsApp Image 2025-05-13 at 13 57 06_faff1f1f](https://github.com/user-attachments/assets/fc54f554-ce8c-4506-8383-881e89383d31)

### Infinity Norm of a Matrix

![WhatsApp Image 2025-05-13 at 13 57 54_eed405aa](https://github.com/user-attachments/assets/38a57010-9ba1-4c7c-9b92-f3310e25fa42)


## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
