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
```
#developed by: THARUN SRIDHAR
#Register No: 212223230230
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)



# 2-Norm of a Matrix
Developed by: THARUN SRIDHAR
RegisterNumber: 212223230230
'''
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,2)
print("%0.2f"%a)




# Infinity Norm of a Matrix
#developed by: THARUN SRIDHAR
#Register no: 212223230230
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)




```
## Output:
### 1-Norm of a Matrix
<br>![image](https://github.com/Tharun0707/Norm-of-a-matrix/assets/145548496/abe2e620-8972-41e9-a61b-7231f8e8490d)

<br>
<br>

### 2-Norm of a Matrix
<br>[image](https://github.com/Tharun0707/Norm-of-a-matrix/assets/145548496/a0235525-ddf0-4fc6-87d1-b263fb8cb7a6)

<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://github.com/Tharun0707/Norm-of-a-matrix/assets/145548496/de7a5faa-b31b-497a-a7b7-bc4c2be6091f)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
