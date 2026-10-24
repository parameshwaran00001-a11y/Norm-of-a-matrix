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
# Register No:26018719
# Developed By:Parameshwaran N
# 1-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
norm="{:.2f}".format(norm1)
print(norm)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Parameshwaran N
RegisterNumber:26018719 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
norm="{:.2f}".format(norm1)
print(norm)

# Type your code here




# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,np.inf)
norm="{:.2f}".format(norm1)
print(norm)





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="740" height="208" alt="Screenshot 2026-10-24 090834" src="https://github.com/user-attachments/assets/26f5581e-8941-4bc7-91a1-043d70bd1591" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="692" height="251" alt="Screenshot 2026-10-24 091628" src="https://github.com/user-attachments/assets/275f0d36-d78e-4287-b91e-40a717340d1a" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="647" height="217" alt="Screenshot 2026-10-24 091742" src="https://github.com/user-attachments/assets/4929bdfd-919f-4920-a7a1-24495d9140fb" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
