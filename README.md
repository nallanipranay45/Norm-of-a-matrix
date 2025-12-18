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
# Register No:25017706
# Developed By:N.lakshmi pranay
# 1-Norm of a Matrix
import numpy as np

A=np.array(eval(input()))

norm1=np.linalg.norm(A,1)

print(norm1)

# 2-Norm of a Matrix

import numpy as np

A=np.array(eval(input()))

norm2=np.linalg.norm(A,2)

print(f"{norm2:.2f}"

# Infinity Norm of a Matrix

import numpy as np

A=np.array(eval(input()))

norminf=np.linalg.norm(A,np.inf)

print(f"{norminf:.2f}")

```
## Output:
### 1-Norm of a Matrix
<img width="1917" height="860" alt="Screenshot 2025-12-18 212651" src="https://github.com/user-attachments/assets/6957a109-0e58-4537-9d0f-bac35e612f69" />


### 2-Norm of a Matrix
<img width="1887" height="913" alt="Screenshot 2025-12-18 212735" src="https://github.com/user-attachments/assets/6e7419ab-b59f-4634-ac63-05b139621255" />


### Infinity Norm of a Matrix
<img width="1876" height="920" alt="Screenshot 2025-12-18 212749" src="https://github.com/user-attachments/assets/a6b50061-bdba-434c-a919-177ccd2c83d1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
