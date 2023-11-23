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
#To find GCD of a number
#Developer name: Thilakeshwaran KP
#Referance number: 23013560

def gcd():
    a=int(input())
    b=int(input())
    while b:
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```

## Output:
![output](/GC-of-two-numbers.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
