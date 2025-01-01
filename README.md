# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	Program 1 

	1.Input and Parsing: The user provides a 2D matrix as input, which is converted from a string into a NumPy array using eval() and np.array().
	2.norm Definition: The -norm is the maximum absolute sum of elements in any column of the matrix.
    3.Computation: Use np.linalg.norm() with ord=1 to calculate thenorm efficiently.
    4.Rounding and Output: Round the computed norm using round() and display it to the user using print().
  
   Program 2

    1.Input Parsing: Take user input as a string,convert it to a Python object using `eval()`, and create a NumPy array.  
    2. \( L^2 \)-Norm Definition: The \( L^2 \)-norm is the square root of the sum of squared elements for a vector or the largest singular value for a matrix.  
    3.Computation: Use `np.linalg.norm(arr, ord=2)` to calculate the \( L^2 \)-norm efficiently.  
    4.Rounding and Output: Round the result to two decimal places using `round()` and print it.  

   Program 3


    1.Input Parsing: Take user input as a string, convert it to a NumPy array using `eval()` and `np.array()`.  
    2.\( L^\infty \)-Norm Definition: The \( L^\infty \)-norm is the maximum absolute value for vectors or the maximum   absolute row sum for matrices.  
    3.Computation: Use `np.linalg.norm(arr, np.inf)` to calculate the \( L^\infty \)-norm.  
    4.Rounding and Output: Round the result using `round()` and print it.


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
