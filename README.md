# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# step 1:
 Define a function.
# step 2:
 Get the two numbers from the user.
# step 3:
 Compare the two values, to find the smaller number.
# step 4:
 Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
# Program to find the gcd of two number using function.
# Developed by: R ABDULLAH
# RegisterNumber: 23013613
def gcd():
num1=int(input())
num2=int(input())
if num1>num2:
min=num2
else:
min=num1
for i in range(1,min+1):
if(num1%i==0 and num2%i==0):
gcd=i
print("GCD of two numbers is:",gcd)
```
## Output:
![Screenshot 2023-12-24 172616](https://github.com/MARXINLIJO/GCD-of-two-numbers/assets/145742540/6672873f-b063-486c-960e-ed20c46a9b70)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
