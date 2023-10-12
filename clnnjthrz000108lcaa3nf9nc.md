---
title: "DAY 25 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Thu Oct 12 2023 19:04:10 GMT+0000 (Coordinated Universal Time)
cuid: clnnjthrz000108lcaa3nf9nc
slug: day-25-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1695835264831/d0cb9153-85f6-4279-94a8-1c76223e9acc.png
tags: python, python3, basics-of-python

---

# Write a Python program to find the median of a given list of numbers:

```python
numbers = [5, 2, 9, 1, 5, 6]


numbers.sort()


n = len(numbers)


if n % 2 == 0:
    
    middle1 = numbers[n // 2 - 1]
    middle2 = numbers[n // 2]
    median = (middle1 + middle2) / 2
else:
   
    median = numbers[n // 2]


print("Median:", median)
```

  

Output :

```python
Median: 5.0
```

---

In the provided code, we begin with a list of numbers, `numbers = [5, 2, 9, 1, 5, 6]`, which is then sorted in ascending order. Subsequently, the length of the sorted list is determined and stored in the variable `n`. A check is performed to ascertain whether the length is even or odd, achieved through the modulo operator (`%`). If the length is even, the median is computed by averaging the two central elements, designated as `middle1` and `middle2`. In the case of an odd length, the median is established by selecting the middle element. Finally, the calculated median value is printed to the console with the label "Median."

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**