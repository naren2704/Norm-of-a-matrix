# Norm of a matrix
# Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

# Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
# Algorithm:
Import numpy module
Get the input matrix using np.array()
Find the norm of the matrix using np.linalg.norm() np.linalg.norm(a,1) for 1-Norm np.linalg.norm(a,2) for 2-Norm np.linalg.norm(a,np.inf) for Infinity-Norm
Print the norm of the matrix in two decimal places.
Program:
# Register No:NARENDRAN B
# Developed By:212222240069
# 1-Norm of a Matrix
``` 
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
``` 




# 2-Norm of a Matrix
```
import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))
```


# Infinity Norm of a Matrix
```

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
``` 





# Output:
# 1-Norm of a Matrix
![image](https://github.com/naren2704/Norm-of-a-matrix/assets/118706984/29d51951-33d4-41a7-bcf8-76e0dac1d22d)


# 2-Norm of a Matrix
![image](https://github.com/naren2704/Norm-of-a-matrix/assets/118706984/72545689-a693-4c48-97b9-ff1ccca9959e)


# Infinity Norm of a Matrix
![image](https://github.com/naren2704/Norm-of-a-matrix/assets/118706984/b906b3ca-10ad-4ea3-b299-7afec264683a)


# Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
