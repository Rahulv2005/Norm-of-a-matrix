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
# Register No:212223240132
# Developed By:RAHUL V
# 1-Norm of a Matrix
import numpy as np 
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}" . format(ans)
print(norm_of_matrix)
```




# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by:RAHUL V
RegisterNumber: 212223240132
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}" . format(ans)
print(norm_of_matrix)

# Type your code here
```





# Infinity Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}" . format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Rahulv2005/Norm-of-a-matrix/assets/152600335/2231c356-e9d2-4cd4-b650-76521d4f98ee)
![image](https://github.com/Rahulv2005/Norm-of-a-matrix/assets/152600335/8e19d68d-b30f-4f33-8b39-444356a58636)


### 2-Norm of a Matrix
![image](https://github.com/Rahulv2005/Norm-of-a-matrix/assets/152600335/5233b366-a6e5-499e-a157-201153adf932)
![image](https://github.com/Rahulv2005/Norm-of-a-matrix/assets/152600335/817f1e42-b306-49dc-90c0-e75350804fca)

### Infinity Norm of a Matrix
![image](https://github.com/Rahulv2005/Norm-of-a-matrix/assets/152600335/0eb0e026-eb29-4f55-9e7e-c8051abc9ab7)
![image](https://github.com/Rahulv2005/Norm-of-a-matrix/assets/152600335/a1de8b02-6879-49cb-9183-a1bbd13061e0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
