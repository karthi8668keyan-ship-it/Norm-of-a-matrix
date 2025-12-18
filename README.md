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
# Register No:25016466
# Developed By:KARTHIKEYAN A
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print(b)



# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(f"{b:.2f}")


# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(b)



```
## Output:
### 1-Norm of a Matrix
<img width="1245" height="832" alt="Screenshot 2025-12-17 144739" src="https://github.com/user-attachments/assets/e84919e8-22ba-4ec8-8bcc-e6f1769ebcf6" />

### 2-Norm of a Matrix
<img width="1236" height="835" alt="Screenshot 2025-12-17 144754" src="https://github.com/user-attachments/assets/cd7c6466-8cc7-4d23-8efb-90866fb5158f" />

### Infinity Norm of a Matrix
<img width="1260" height="839" alt="Screenshot 2025-12-17 144805" src="https://github.com/user-attachments/assets/5f391ca5-9a35-4a43-9566-252ab6ed809d" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
