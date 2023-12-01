# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step 1:
1. Define a function.
## step 2:
2. Get the two numbers from the user.
## step 3:
3. Compare the two values, to find the smaller number.
## step 4:
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#GCD of two numbers
#Developed by:S.kathiranand
#Reg No:23013711
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1,smaller+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:
![output](https://github.com/Skathiranand/GCD-of-two-numbers/assets/147141136/35f6ebe8-c996-4ce2-bb60-977bfe737e82)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
