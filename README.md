# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
import the numpy values 
### Step 2:
prepare the list from each of the rank 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
circulate the values   
### Step 6: 
End the program
## Program:
~~~
#Program to circulate N values.
#Developed by: sharmila A
#RegisterNumber:21004420
def circulate():
    n=int(input())
    l=[10,20,30,40,50,60]
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~
## Output:

## Result:
