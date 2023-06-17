---
title: "DAY 11 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Sat Jun 17 2023 18:31:01 GMT+0000 (Coordinated Universal Time)
cuid: clj0c46wf000109l39ukl9fqy
slug: day-11-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1687024834623/f45b072e-95c9-4bf4-a394-a1c1164af51a.png
tags: python, prime, python-beginner, basics-of-python

---

# Write a Python program to check whether a given number is a prime number or not:-

```python
num = int(input("Enter a number: "))

result = ""
i = 2

while i * i <= num:
    if num % i == 0:
        result = "not "
        break
    i += 1

if num < 2 or result == "not ":
    result = "not " + result

print(num, "is", result + "a prime number.")
```

output :

```python

Enter a number: 5
5 is a prime number.
```

**The code iterates through the numbers starting from 2 and checks if any of them evenly divide the input number. If a divisor is found, it means the number is not prime. Otherwise, the number is considered prime.**

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**