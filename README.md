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

Program to find the square root for the given number(newton's method) using function.
Developed by: ARHAM S
RegisterNumber:  212222110005
num1 = int(input())
x =1
for i in range(100):
    x =0.5*(x+num1/x)
print("Square root of the number:",x)

```

## Output:
![Screenshot (19)2](https://github.com/arhamshajahan/Square-root-of-a-number/assets/127313881/94060ac4-a30b-4872-a49f-1ca7fce88e75)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
