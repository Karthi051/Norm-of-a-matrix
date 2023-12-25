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
# Register No:23013936
# Developed By:karthi keyan k
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
![image](https://github.com/Karthi051/Norm-of-a-matrix/assets/148327224/68480136-c291-45c3-b2e3-e13efaadd662)


### 2-Norm of a Matrix
![image](https://github.com/Karthi051/Norm-of-a-matrix/assets/148327224/35bec954-c71e-4d03-b5cb-f2e7f316b053)


### Infinity Norm of a Matrix
![image](https://github.com/Karthi051/Norm-of-a-matrix/assets/148327224/ff1bc57d-0552-4b92-ae4f-e66492f782b3)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
