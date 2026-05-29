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
# Register No:212225230104
# Developed By:INIYA S
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(round(two_matrix,2))




# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print(round(inf_matrix,2))



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1211" height="793" alt="image" src="https://github.com/user-attachments/assets/71adbfee-d9e9-47b1-a580-089e1f68fa5a" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1236" height="842" alt="image" src="https://github.com/user-attachments/assets/dda502f6-4ceb-45ba-80dd-c8a4ec3aa38a" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1211" height="767" alt="image" src="https://github.com/user-attachments/assets/25a6a289-c3e4-4f18-9b74-de636ef19416" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
