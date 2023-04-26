---
title: "DAY 9 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Wed Apr 26 2023 17:05:51 GMT+0000 (Coordinated Universal Time)
cuid: clgxy6d8z000p09mmchce41i2
slug: day-9-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682361024247/98cdec08-e422-4ee8-ac92-176c6c9b9030.png
tags: python, 100daysofcode, prime-number-checker, basics-of-python, day9

---

# Write a Python program to check whether a given number is a prime number or not :

```python
num = int(input("Enter a number: "))

if num > 1:
    for i in range(2, num):
        if (num % i) == 0:
            print(num, "is not a prime number")
            break
    else:
        print(num, "is a prime number")
else:
    print(num, "is not a prime number")
```

Output :

```python
Enter a number: 9
9 is not a prime number
```

1. The code prompts the user to enter an integer value using the 'input()' function and stores the input value in the variable 'num' after converting it to an integer using the 'int()' function.
    
2. The 'if' statement checks whether the input number 'num' is greater than 1. If the number is greater than 1, the code proceeds with checking whether it is a prime number or not. If the number is less than or equal to 1, the code prints a message stating that the input number is not a prime number since prime numbers are defined as positive integers greater than 1.
    
3. The 'for' loop starts from 2 and iterates up to 'num' - 1, checking for each number in between whether it divides 'num' evenly or not.
    
4. The 'if' statement inside the loop checks if the current value of 'i' divides 'num' evenly or not. If 'num' is evenly divisible by 'i', it means that 'num' is not a prime number. The code prints a message stating that the input number is not prime and breaks out of the loop.
    
5. If the loop completes its iterations without finding any factor of 'num', it means that 'num' is a prime number. The code prints a message stating that the input number is prime.
    
6. If the input number is less than or equal to 1, the code prints a message stating that the input number is not a prime number since prime numbers are defined as positive integers greater than 1.
    

---

If you are a beginner and want to know more about Python programming, you can read my [Basics of Python](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [part 1](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [part 15](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

* ---
    
    **HAPPY LEARNING !!!**