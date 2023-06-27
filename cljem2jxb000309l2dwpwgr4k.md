---
title: "DAY 13 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Tue Jun 27 2023 18:18:27 GMT+0000 (Coordinated Universal Time)
cuid: cljem2jxb000309l2dwpwgr4k
slug: day-13-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1687813015050/1ad276f2-2ba2-4dfd-9fc4-b7471eee34c3.png
tags: python, python3, python-beginner, basics-of-python, day13

---

# Write a Python program to find the sum of all even numbers between 1 and a given number.

```python
n=int(input("enter the number"))
sum=0
for i in range(0,n+1):
    if i%2==0:
        sum+=i
print(sum)
```

Output :

```python
enter the number10
30
```

1. The user is prompted to enter a number, which is stored in the variable n.
    
2. The variable sum is initialized to 0. This variable will store the sum of all even numbers.
    
3. A loop is set up using the range function with the parameter n+1. This loop will iterate over all numbers from 0 to n, inclusive.
    
4. For each iteration of the loop, the current number i is checked to see if it is even by using the condition i % 2 == 0. The % operator calculates the remainder when i is divided by 2, so if the remainder is 0, it means i is even.
    
5. If i is even, it is added to the sum variable using the += shorthand operator, which adds the value of i to the current value of the sum.
    
6. After the loop finishes, the final value of the sum is printed, which represents the sum of all even numbers from 0 to n.
    

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**