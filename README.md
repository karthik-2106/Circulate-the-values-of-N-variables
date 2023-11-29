# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Program the code with def circulate.
### Step 2:
Get the value from the user for the number of rotation. 
### Step 3: 
Print the circulating values
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Evaluate the a input
### Step 6:
Enter integer(n) in input 
## Program:
``````
#Program to circulate N values.
#Developed by: KARTHIKEYAN M
#RegisterNumber: 23005191
def circulate():
    l=eval(input())
    n=int(input())
    z=l[n:]+l[:n]
    print("After circulating the values are:",z)
``````
## Output:
![OUTPUT](/circulate.png)
## Result:
Thus the circulate the values of N variables are successfully executed.