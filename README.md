# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1:
Get two value from the user

### Step 2:
Circulate a value variable

### Step 3:
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5:
Print the value after

### Step 6:
End of the program

Program: 
## Program:
#Program to circulate N values.
#Developed by: AARON I
#RegisterNumber:23002289
```
def circulate():
   a=eval(input())
   n=int(input())
   for i in range(n):
      x=a[0]
      del a[0]
      a.append(x)
   print("After circulating the values are:",a)
```

## Output:
![output](/Screenshot%202023-07-26%20125444.png)

## Result:
Thus the circulate the values of N variables  are successfully executed
