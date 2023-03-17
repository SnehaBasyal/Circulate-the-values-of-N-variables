# Circulate-the-values-of-N-variables

## Aim:
To write a python program to circulate the n variables using function concept

## Equipment’s required:
PC
Anaconda - Python 3.7

## Algorithm: 
### Step 1: 
Get the value from the user for the list 
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Define the function circulate
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the circulated values
### Step 6: 
End the program

## Program:
```
#Program to circulate N values.
#Developed by: Sneha Basyal M
#RegisterNumber:212222240101

list1=eval(input())
n=int(input())
def circulate():
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![Circulate-the-values-of-N-variables](out2.png)

## Result:
Thus the program to circulate N values is successfully executed.
