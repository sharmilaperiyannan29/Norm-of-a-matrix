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
![s1](https://github.com/user-attachments/assets/20340b9b-4a10-4ded-9160-afe709ba23ba)


### 2-Norm of a Matrix
![s2](https://github.com/user-attachments/assets/c288a8ae-5ea5-4c8f-9921-e0b68202236e)


### Infinity Norm of a Matrix
![s3](https://github.com/user-attachments/assets/0a7ce0ff-4d37-433d-ac3f-d2126fc7c073)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
