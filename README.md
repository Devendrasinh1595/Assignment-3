# Assignment-3
# Task 1

n=int(input('Enter a Number : '))
def factorial(n):
    if n<2:
        return 1
    else:
        return n*(factorial(n-1))
Ans=factorial(n)
print('Factorial of ',n,'is : ',Ans)

# Task 2
a=int(input('Enter a Number : '))
from math import *
print('Squre root : ',sqrt(a))
print('Logarithm : ',log(a,e))
print('Sine : ',sin(a))
