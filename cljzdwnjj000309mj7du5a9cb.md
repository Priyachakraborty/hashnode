---
title: "DAY 21 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Wed Jul 12 2023 07:13:05 GMT+0000 (Coordinated Universal Time)
cuid: cljzdwnjj000309mj7du5a9cb
slug: day-21-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1688147155105/8e1ecfb7-5a77-4943-9703-53642b5e3e14.png
tags: python3, python-beginner, basics-of-python, day21

---

# Write a Python program to find the missing number in a given array of integers.

```python
array = [1,2,3,4,5,7,8,9]
n = len(array) + 1
total_sum = (n * (n + 1)) // 2
array_sum = sum(array)
missing_number = total_sum - array_sum
print(missing_number)
```

Output :

```python
6
```

The code calculates the missing number in a given array of integers. It does so by finding the sum of integers from 1 to n, where n is the length of the array plus one. Then, it calculates the sum of the given array. The missing number is obtained by subtracting the array sum from the total sum of integers. Finally, the code prints the missing number.

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**