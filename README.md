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
# Register No:22009062
# Developed By:Gokul J
# 1-Norm of a Matrix
import numpy as np 

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![norm](https://user-images.githubusercontent.com/121165938/214768861-c7d1426d-1a95-42ca-86b6-d9f30bf231bd.png)




### 2-Norm of a Matrix
![norm mat](https://user-images.githubusercontent.com/121165938/214768957-60a2e555-b71f-4342-9085-0e97d53721f1.png)


### Infinity Norm of a Matrix
![norm matrix](https://user-images.githubusercontent.com/121165938/214769032-a566be4e-5404-4342-9917-108cfcb42e1f.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
