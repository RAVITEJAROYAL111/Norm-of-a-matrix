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
# Register No:25011599
# Developed By:RAVI TEJA ROYAL
# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
<br><img width="907" height="567" alt="image" src="https://github.com/user-attachments/assets/a856ffca-99e3-48e8-acb1-f283500005a4" />
### 2-Norm of a Matrix
<br><img width="839" height="598" alt="image" src="https://github.com/user-attachments/assets/7074ec34-c338-4d23-a1b8-72c5823f5153" />


### Infinity Norm of a Matrix
<br><img width="865" height="586" alt="image" src="https://github.com/user-attachments/assets/c1856ebb-413d-4aa3-82fe-b5a950c0992b" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
