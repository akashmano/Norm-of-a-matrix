# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212223240003
# Developed By:akash.m

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
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
![Screenshot 2023-12-29 003928](https://github.com/PremkumarG3/Norm-of-a-matrix/assets/138955646/d3cace19-2871-438d-8754-332f628b98ca)
### 2-Norm of a Matrix
![Screenshot 2023-12-29 003942](https://github.com/PremkumarG3/Norm-of-a-matrix/assets/138955646/b5cfadb2-03fe-42b3-b6b5-20dcb4ef5bfc)
### Infinity Norm of a Matrix
![Screenshot 2023-12-29 003956](https://github.com/PremkumarG3/Norm-of-a-matrix/assets/138955646/7ac8f7af-eadc-4440-bdae-5d934c9ac412)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
