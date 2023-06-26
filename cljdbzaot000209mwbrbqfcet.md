---
title: "DAY 12 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Mon Jun 26 2023 20:48:13 GMT+0000 (Coordinated Universal Time)
cuid: cljdbzaot000209mwbrbqfcet
slug: day-12-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1687812384029/c7338b8e-be9e-4f6d-9473-3c2f1fc5a3d6.png
tags: python, python-beginner, basics-of-python, day12

---

## Write a Python program to Check whether the given number is prime or not.

```python

n=int(input("Enter the number: "))

if n < 2 :
    is_prime= False
else:
    is_prime= True
    for i in range(2,int(n**0.5)+1):
        if n%i==0:
            is_prime= False
            break

if is_prime:
    print("YES,Number is Prime Number")
else :
    print('NO,Number is not Prime Number')
```

Output :

```python
Enter the number: 8
NO,Number is not Prime Number

Enter the number: 7
YES,Number is Prime Number
```

The program prompts the user to enter a number, which is stored in the variable n.

Then, it checks if the number is less than 2. If it is, the variable is\_prime is set to False since prime numbers are defined as integers greater than 1.

If the number is 2 or greater, the variable is\_prime is initially set to True. It then proceeds to iterate from 2 to the square root of the number (inclusive) using a for loop. Within the loop, it checks if the number is divisible by the current divisor (i). If it is, the variable is\_prime is set to False, indicating that the number is not prime, and the loop is terminated using break.

Finally, outside the loop, the program checks the value of is\_prime. If it is True, it prints that the number is a prime number. Otherwise, it prints that the number is not a prime number.

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**