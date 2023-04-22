---
title: "DAY 6 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Sat Apr 22 2023 11:41:31 GMT+0000 (Coordinated Universal Time)
cuid: clgrwtvij000009l9d7ozd6to
slug: day-6-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682161968943/bc7a68b1-2d57-4d51-a642-38d7caab70db.png
tags: python, beginner, 100daysofcode, basics-of-python, day6

---

# Write a Python program to find the factorial of a given number:

```python
n=int(input('Enter the number :  '))
fact=1
for i in range(1,n+1):
    fact=fact*i
print(fact)
```

Output :

```python

Enter the number :  6
720
```

This is a Python program to calculate the factorial of a given number. The user is prompted to enter a number and the program uses a for loop to calculate the factorial. The factorial of a number is the product of all positive integers up to and including that number.

Let's go through the code line by line:

1. `n=int(input('Enter the number: '))` - This line prompts the user to enter a number and stores it in the variable `n`. The `int` function is used to convert the input to an integer.
    
2. `fact=1` - This line initializes the variable `fact` to 1. This variable will be used to store the factorial.
    
3. `for i in range(1,n+1):` - This line sets up a for loop that will iterate over the range of numbers from 1 to `n+1`.
    
4. `fact=fact*i` - This line multiplies the current value of `fact` by the loop variable `i` and stores the result back in `fact`.
    
5. `print(fact)` - This line prints the final value of a `fact`, which is the factorial of the input number.
    

Overall, this program is a simple and effective way to calculate the factorial of a given number in Python.

---

If you are a beginner and want to know more about Python programming, you can read my [Basics of Python](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [part 1](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [part 15](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**