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
# Register No:25011912
# Developed By:Gianna J
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)

# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm2 = np.linalg.norm(A,2)
print(f"{norm2:.2f}")

# Infinity Norm of a Matrix

import numpy as np 
A = np.array(eval(input()))
norm = np.linalg.norm(A,np.inf)
print(norm)

```
## Output:
### 1-Norm of a Matrix
<img width="1899" height="982" alt="Screenshot 2025-11-26 112741" src="https://github.com/user-attachments/assets/6ea0938d-de2b-46e0-8455-85f456664a01" />


### 2-Norm of a Matrix
<img width="1885" height="922" alt="Screenshot 2025-11-26 112801" src="https://github.com/user-attachments/assets/eb783d58-b3f5-46a7-8275-e700caec65ec" />


### Infinity Norm of a Matrix
<img width="1885" height="920" alt="Screenshot 2025-11-26 112824" src="https://github.com/user-attachments/assets/4c29008b-7bd5-4895-8d00-75ed83cba19a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
