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

# 1-Norm of a Matrix
```
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```




# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```




# Infinity Norm of a Matrix
```
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)







```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-12-01 213156](https://github.com/user-attachments/assets/af334e48-d518-4825-b6e2-4f06e78b4993)


### 2-Norm of a Matrix

![Screenshot 2024-12-01 213210](https://github.com/user-attachments/assets/03baf831-22bb-40d5-a946-047d9b80fb40)


### Infinity Norm of a Matrix

![Screenshot 2024-12-01 213221](https://github.com/user-attachments/assets/2bdd5b83-02e3-4fa5-83bc-e2ee77476335)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
