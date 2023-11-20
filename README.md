# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the programme
### Step 2: 
get the inputs from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using concatication operation display the entire rotated list

### Step 6: 
stop the programme
## Program:
```
#Program to circulate N values.
#Developed by: LEVAKU LAKSHMI MOUNIKA
#RegisterNumber:23004124
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## OUTPUT:
![Screenshot 2023-11-20 090745](https://github.com/mounika2005/Circulate-the-values-of-N-variables/assets/145633112/b3f1a7ee-90d1-422d-95d2-bad7c3583f5a)

## Result:
thus the python program for circulating the values of n variables is exicuted successfully
