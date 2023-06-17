# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Get the input matrix from the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
    #Program to find the eigen values and eigen vectors.
    #Developed by: Dhiyaneshwar
    #RegisterNumber: 212222110009
    import numpy as np
    A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
    result,res=np.linalg.eig(A)
    print("Eigen values are {0} and Eigen Vectors are {1}".format(result,res))

## Output:
![image](https://github.com/Dhiyanesh24/EIGENVALUES-AND-EIGENVECTORS/assets/118362288/bdcab808-8a9c-4e62-a24d-ea6ff3efd132)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
