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
Developed by: jagadheesh kumar T
RegisterNumber:  212225040139
*/
def gcd(a, b):
    while b:
        a, b = b, a % b
    return a

x = int(input())
y = int(input())

print("GCD =", gcd(x, y))
```

## Output:
<img width="473" height="174" alt="image" src="https://github.com/user-attachments/assets/d4fc0013-60be-4ea5-b64e-30d4d40ce47e" />




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
