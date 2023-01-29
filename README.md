# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by:S Devesh sharma
RegisterNumber: 22005350
*/
def gcd():
    n=int(input())
    m=int(input())
    if (n>m):
        min=m
    else:
        min=n
    for i in range (1,min+1):
        if (n%i==0 and m%i==0):
            o=i
    print("GCD of two numbers is:",o)
```

## Output:
![gcd](https://user-images.githubusercontent.com/121490523/215334998-41c451cd-4ffe-40b8-a8e7-cc0dd9feb276.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
