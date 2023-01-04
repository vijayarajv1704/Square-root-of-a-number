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
Developed by: 
RegisterNumber:  
*/
```
#program to find the square root for the given number(newton's method) using function.

#Developed by:vijayaraj.v
#RegisterNumber:22001903

n=int(input())

x=1

for i in range(100):
    
    x=0.5*(x+n/x)

print("Square root of the number:",x)

## Output:
![gcd of two number](./Screenshot%20from%202023-01-04%2010-43-46.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
