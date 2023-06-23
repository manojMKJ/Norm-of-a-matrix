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
# Register No:22005014
# Developed By:Manoj kumar G
# 1-Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```




# 2-Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


## Output:
![image](https://github.com/manojMKJ/Norm-of-a-matrix/assets/120717614/742a2be5-7130-443a-b0e5-f35a8661632d)
![image](https://github.com/manojMKJ/Norm-of-a-matrix/assets/120717614/0b9bb14d-f710-4438-930f-5d6514f01261)
![image](https://github.com/manojMKJ/Norm-of-a-matrix/assets/120717614/95648fc5-6a9d-4700-838d-d84f84a7ae1e)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
