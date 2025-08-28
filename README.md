# Python Basics – Even/Odd Checker & Sum of Numbers

This repository contains two simple Python programs:

1. Even or Odd Checker – Checks if a given number is even or odd.  
2. Sum of Numbers – Calculates the sum of numbers from 1 to 50.

---

## task 1: Even or Odd Checker

### Code:
a = int(input('enter a number: '))

if a % 2 == 0:
    print(a, 'is even')
else:
    print(a, 'is odd')
# Sum of Numbers from 1 to 50

This is a simple Python program that calculates the sum of numbers from **1 to 50**.

---

## Task 2: Sum of Numbers from 1 to 50
### Code:
totalsum = 0
for i in range(1, 51):
    totalsum = totalsum + i
print('sum of numbers from 1 to 50 is :', totalsum)
