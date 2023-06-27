---
title: "DAY 14 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Tue Jun 27 2023 18:37:36 GMT+0000 (Coordinated Universal Time)
cuid: cljemr6pc000609kza2t8cb6c
slug: day-14-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1687890478967/f854577a-c5ea-4245-9f05-0fdfefbd9aa7.png
tags: python, python3, basics, basics-of-python, day14

---

# Write a Python program to find the sum of all odd numbers between 1 and a given number.

```python
n=int(input("enter the number"))
sum=0
for i in range(0,n+1):
    if i%2!=0:
        sum+=i
print(sum)
```

Output :

```python
enter the number10
25
```

1. The input() function is used to get input from the user, and int() is used to convert the input to an integer.
    
2. Initializes a variable called sum to 0. This variable will be used to keep track of the sum of odd numbers.
    
3. The loop variable is i, which takes on the values from 0 to n in each iteration.
    
4. Checks if the current value of i is not divisible by 2, i.e., if it is an odd number.
    
5. If i is an odd number, it is added to the current value of the sum.
    

After the loop completes, the final value of the sum is printed.

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**