# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function to cirulate the variables 
### Step 2: 
Initialize a list from the user using eval
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
We do this initializing a variable l1 and adding the values before index and after the index in the list.
### Step 6: 
Print the value of l1
## Program:
```
#Program to circulate N values.
#Developed by: Meyyappan.T
#RegisterNumber:23000788
def circulate():
     l=list(eval(input()))
     n=int(input())
     l1=l[n:]+l[:n]
     print("After circulating the values are:",l1)
```

## Output:
![Alt text](ex02pythongit.png)


## Result:
Thus the python program for circulate the values of n variables is executed successfully
