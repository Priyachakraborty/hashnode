---
title: "DAY 24 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Mon Sep 25 2023 18:04:03 GMT+0000 (Coordinated Universal Time)
cuid: clmz76p6g00040aid4ehm0gag
slug: day-24-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/842ofHC6MaI/upload/9db2b2498bebd0e6e7d57d8ddba5c320.jpeg
tags: python, python3, basics-of-python

---

# Write a Python program to find the length of the longest substring without repeating characters in a given string

```python
input_string = "abcabcbb"

char_index = {}
max_length = 0
start = 0

for end in range(len(input_string)):
    if input_string[end] in char_index and char_index[input_string[end]] >= start:
        start = char_index[input_string[end]] + 1

    char_index[input_string[end]] = end
    max_length = max(max_length, end - start + 1)

print("Length of the longest substring without repeating characters:", max_length)
```

Output:

```python
Length of the longest substring without repeating characters: 3
```

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**