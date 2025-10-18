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
# Register No: 212224230107
# Developed By: JOSHITHA SHREE BS
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="1027" height="176" alt="image" src="https://github.com/user-attachments/assets/ae842750-d7e4-4057-b637-9dcfdc51deb3" />

### 2-Norm of a Matrix
<img width="1022" height="211" alt="image" src="https://github.com/user-attachments/assets/0226a2e0-c854-4041-b218-51120d72e411" />


### Infinity Norm of a Matrix
<img width="1031" height="172" alt="image" src="https://github.com/user-attachments/assets/35ccc0c9-7a89-4299-95ed-9b363fa35efa" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
