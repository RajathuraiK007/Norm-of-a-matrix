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
# Register No: 212225100036
# Developed By: Rajathurai K
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
res_1=np.linalg.norm(mat,1)
print("The 1-Norm of the given matrix is {:.2f}".format(res_1))



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
res_2=np.linalg.norm(mat,2)
print("The 2-Norm of the given matrix is {:.2f}".format(res_2))



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
res_inf=np.linalg.norm(mat,np.inf)
print("The infinity norm of the given matrix is {:.2f}".format(res_inf))




```
## Output:
### 1-Norm of a Matrix
<img width="1504" height="307" alt="image" src="https://github.com/user-attachments/assets/42fd6a88-8bee-48e0-a9ed-491c3f0f5c4e" />


### 2-Norm of a Matrix
<img width="1502" height="108" alt="image" src="https://github.com/user-attachments/assets/ba04fc86-d15e-4c46-adf5-426399415a01" />

### Infinity Norm of a Matrix
<img width="1485" height="98" alt="image" src="https://github.com/user-attachments/assets/c9a40af2-9504-49bf-98e2-f84555529c7a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
