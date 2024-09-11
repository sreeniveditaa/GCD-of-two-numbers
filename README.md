# DATE:
# EXP 04 : Find the GCD of two numbers

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
Developed by: SREE NIVEDITAA SARAVANAN
RegisterNumber: 212223230213
*/
```
```
def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller=n2
    else:
        samller=n1
    for i in range(1,smaller+1):
        if n1%i==0 and n2%i==0:
            gcd1=i
    print(f"GCD of two numbers is: {gcd1}")
```

## Output:

![image](https://github.com/user-attachments/assets/b2441b01-c9d9-468f-a7c5-0143ec4ea18c)

![image](https://github.com/user-attachments/assets/c94032a0-5ac7-43a0-a4b7-fb46d0ae14bc)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
