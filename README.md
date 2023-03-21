# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list
### Step 4: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by:Kancharla Narmadha 
#RegisterNumber:212222110016
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:




![record 2](https://user-images.githubusercontent.com/119559316/226272387-9dd4cd3a-4f6e-4ccd-9ba1-a243d929add5.png)

## Result:
Thus the circulate n variables are executed successfully
