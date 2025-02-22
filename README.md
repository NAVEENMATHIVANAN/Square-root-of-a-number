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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: NAVEEN KUMAR M
RegisterNumber:  212222110028

def sq(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",sq(a))

*/
```

## Output:
![gcd of two number](gcd.png)

![image](https://user-images.githubusercontent.com/119394582/235068676-c729eb07-c9ca-4e42-9459-5f0b3bce02bc.png)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
