---
title: "DAY 2 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Tue Apr 04 2023 00:30:38 GMT+0000 (Coordinated Universal Time)
cuid: clg1ixsbh035sdinv3dw0ghf2
slug: day-2-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1680509255407/f9431989-b064-4f2c-8028-860e7b32a577.png
tags: python, programming-languages, coding-challenge, python-beginner, day2

---

## *Write a Python program to find the sum of all numbers between 1 and a given number*:-

---

```python
n=int(input('Enter the number : '))
sum=0
for i in range(1,n+1):
    sum=sum+i 
print(sum)
```

### *Output* :

```python
Enter the number : 10
55
```

Here's a line-by-line explanation of what the code does:

1. `n=int(input('Enter the number: ')):` This line prompts the user to enter a number and stores it in the variable `n`. The `int()` function is used to convert the user input, which is a string, to an integer.
    
2. `sum=0`: This line initializes the variable `sum` to 0. This variable will be used to store the sum of all integers from 1 to `n`.
    
3. `for i in range(1,n+1):`: This line starts a for loop that iterates over all integers from 1 up to and including `n`. The `range()` function generates a sequence of integers from 1 to `n`, and the loop variable `i` take on each value in this sequence in turn.
    
4. `sum=sum+i`: This line adds the current value of `i` to the running total stored in the variable `sum`.
    
5. `print(sum)`: This line prints the final value of `sum`, which is the sum of all integers from 1 to `n`.
    

Overall, this code calculates the sum of all integers from 1 to `n` using a simple loop and variable manipulation.

---

If you are a beginner and want to know more about python programming, you can read my [basics of python](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [part 1](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [part 15](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

Happy Learning !!!