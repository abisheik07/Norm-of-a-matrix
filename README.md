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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np 
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(round(result))



# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(round(result,2))




# Infinity Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(round(result))




```
## Output:
### 1-Norm of a Matrix
![](<Screenshot 2024-12-24 222326.png>)
<br>
<br>

### 2-Norm of a Matrix![](<Screenshot 2024-12-24 222342.png>)
<br>
<br>
<br>

### Infinity Norm of a Matrix![](<Screenshot 2024-12-24 222349.png>)
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
