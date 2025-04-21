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
# Register No:SWETHA S V
# Developed By: 212224230285
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
<br>![Screenshot 2025-04-21 223154](https://github.com/user-attachments/assets/4e603058-235f-4bb3-8a7e-4e802a9e0933)

<br>
<br>

### 2-Norm of a Matrix
<br>

<br>![Screenshot 2025-04-21 223212](https://github.com/user-attachments/assets/91898503-48ce-4cb7-ad44-cb2ac1a329ae)

<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2025-04-21 223225](https://github.com/user-attachments/assets/ac6298dc-6dae-41ef-8590-33ffb661bba1)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
