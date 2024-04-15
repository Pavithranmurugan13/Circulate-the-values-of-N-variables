Circulate the values of N variables
Aim:
To write a python program to circulate the n variables using function concept

Equipment’s required:
PC Anaconda - Python 3.7

Algorithm:
Step 1:
Get the two values from the user.

Step 2:
Assign the value of second variable to a temporary variable.

Step 3:
Get the value from the user for the number of rotation

Step 4:
Using the slicing concept rotate the list

step 5:
Print the values it would be interchanged

Program:
#program to ciculate N values.
#Developed by: PAVITHRAN M J
#Register Number:212223240112.

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
Output:
![Screenshot 2024-04-15 133114](https://github.com/Pavithranmurugan13/Circulate-the-values-of-N-variables/assets/163802201/2031e5d6-1d2c-4fac-b4d6-06be054e8154)

Result:
Thus circulating n variables are successfully executed
