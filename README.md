# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to use the builtin functions for calculation
### Step 2: prepare the lists from each linear equation and assign in np.array()
### Step 3: using the np.linalg.solve(),we can find the solutions
### Step 4: end the changes

## Program:
~~~python
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]]) 
s=np.linalg.inv(A)
print(s)
~~~
## Output:
![inversematrix](https://user-images.githubusercontent.com/93978702/155524521-adc1be36-b88d-49c1-bfc8-50e48ead0da2.jpg)


## Result:
Thus the inverse of given matrix is successfully solved using python program

