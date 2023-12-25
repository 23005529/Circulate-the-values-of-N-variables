# Circulate-the-values-of-N-variables
NAME : ALIYA SHEEMA

REFERENCE NUMBER : 23005529

DEPARTMENT : AIDS
# Aim:
To write a python program to circulate the n variables using function concept
# Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define function circulate().

### Step 2: 
Get the input from the user for the list.

### Step 3: 
Get the value from the user for the number of rotation.

### Step 4: 
Using the slicing concept rotate the list.

### Step 5: 
Print the result.

### Step 6: 
Call the function circulate().

# Program:
``````
#Program to circulate N values.
#Developed by: ALIYA SHEEMA
#RegisterNumber: 23005529
def circulate():
    l=eval(input())
    n=int(input())
    out=l[n:]+l[:n]
    print("After circulating the values are: {}".format(out))
``````
# Output:

![output](https://github.com/23005529/Circulate-the-values-of-N-variables/assets/139842207/cae067e1-1316-4396-ac92-9ba8de14bb8e)


# Result:
The result has been successfully verified.
