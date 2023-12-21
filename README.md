# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Program to find the solution for the given linear equations.<br>
#Developed by:Sanjay sivaramakrishnan M<br>
#RegisterNumber:23013798<br>
import numpy as np<br>
<br>
x =np.array([[1,3],[2,5]])<br>
y =np.array([5,-3])<br>
result = np.linalg.solve(x,y);<br>
print(result)<br>
## Output:
![image](https://github.com/sanjaysivaramakrishnan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/151629616/aa321cc3-f362-4f87-8209-ec99555f7b57)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

