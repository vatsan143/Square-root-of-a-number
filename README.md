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

Program to find the square root for the given number(newton's method) using function.

Developed by: SRIVATSAN G 

RegisterNumber:  2122232303216

```
def newton_method(num,num_iters=100):
    a=float(num)
    for i in range(num_iters):
        num=0.5*(num +a/num)
    return num
a=int(input())
print("Square root of the number:",newton_method(a))
```


## Output:
![SQAURE-ROOT-OF-A-NUMBER ](https://github.com/vatsan143/Square-root-of-a-number/assets/147368204/fed82f09-646a-42c9-b4ba-8d6231d1d9cc)





## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
