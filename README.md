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
# Register No:212225230261
# Developed By:Sharmila P
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





## Output:
### 1-Norm of a Matrix
![s1](https://github.com/user-attachments/assets/93f61611-21e2-47d4-a9f3-1dbfa9f4b6bb)

### 2-Norm of a Matrix
![s2](https://github.com/user-attachments/assets/18eb1050-6f82-435b-bef7-4cab8bebff32)

###Infinity Norm of a Matrix


![s3](https://github.com/user-attachments/assets/8a4bfb6e-6f7f-4d54-a00e-2c3291c77720)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
