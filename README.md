# Norm of a matrix
NAME: DEVA DHRSHINI I

REGISTER NO: 212223240026

DEPARTMENT: AIML
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
```
# Register No:212223240026
# Developed By:DEVA DHARSHINI I
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
![Screenshot 2024-05-05 171505](https://github.com/deesk13/Norm-of-a-matrix/assets/150927063/c1b2863c-07f7-4d18-ba13-5e14fa37447f)

### 2-Norm of a Matrix
![Screenshot 2024-05-05 171525](https://github.com/deesk13/Norm-of-a-matrix/assets/150927063/58f73383-8861-4db3-9f86-f085b3855fb0)


### Infinity Norm of a Matrix
![Screenshot 2024-05-05 171539](https://github.com/deesk13/Norm-of-a-matrix/assets/150927063/c0893c70-ad7a-4428-a9e9-1ceb4254f99a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
