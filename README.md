# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
#Program to to find the square root for the given number(newton's method) using function.
#Developed by: Senthil Kumar S
#RegisterNumber: 21500410

def fun():
    x=int(input())
    y=x
    for i in range(10):
      x=0.5*(x+y/x)
    return x
print("Square root of the number:",fun())
```

## Output:
![square](https://user-images.githubusercontent.com/93860256/154271475-eeee0319-fcc4-4666-9168-dcb2ace2e856.PNG)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
