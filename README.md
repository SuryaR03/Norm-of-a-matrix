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
# Register No: 23013019
# Developed By: Surya R
# 1-Norm of a Matrix
'''
program to find 1-norm of matrix
Developed by:Surya R
RegisterNumber:23013019
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Surya R
RegisterNumber: 23013019
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix

'''
program to find infinity of matrix
Developed by:Surya R
RegisterNumber:23013019
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-21 165457](https://github.com/SuryaR03/Norm-of-a-matrix/assets/147140237/f1bf73d2-b9ea-4587-8049-c419453471f6)


### 2-Norm of a Matrix
![Screenshot 2023-12-21 165518](https://github.com/SuryaR03/Norm-of-a-matrix/assets/147140237/8ce1336e-a8d3-4564-8e07-4b691d2addae)


### Infinity Norm of a Matrix
![Screenshot 2023-12-21 165533](https://github.com/SuryaR03/Norm-of-a-matrix/assets/147140237/dc3bf5df-343c-4019-8e5a-b30523604882)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
