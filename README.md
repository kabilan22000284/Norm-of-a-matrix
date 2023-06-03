# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.Get the input matrix using np.array()
2.Find the 2-norm of the matrix using np.linalg.norm()
3.Print the norm of the matrix in two decimal places.	
## Program:
# 1-Norm of a Matrix
```
Program to find the 1-Norm of a matrix 
Developed by:SWETHA N
Register Number:212222100018
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: Kabilan V
RegisterNumber: 212222100018
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
Program to find infinity of a matrix.
Developed by: Kabilan V
RegisterNumber: 212222100018
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot (40)](https://github.com/kabilan22000284/Norm-of-a-matrix/assets/123469171/4e477c19-ad7c-4099-80be-fe63d454fc6c)
### 2-Norm of a Matrix
![Screenshot (41)](https://github.com/kabilan22000284/Norm-of-a-matrix/assets/123469171/3dae55af-01b3-48a8-bb88-139fa9b8750b)
### Infinity Norm of a Matrix!
![Screenshot (42)](https://github.com/kabilan22000284/Norm-of-a-matrix/assets/123469171/ac347c8f-65d4-4cdc-97ae-79f35533f369)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
