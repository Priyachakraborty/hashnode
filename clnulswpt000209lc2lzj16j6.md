---
title: "DAY 27 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Tue Oct 17 2023 17:34:05 GMT+0000 (Coordinated Universal Time)
cuid: clnulswpt000209lc2lzj16j6
slug: day-27-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1697475375280/f482b6ea-f647-4053-876b-b27a4a3a6f78.png
tags: python, python3, python-beginner, basics-of-python

---

# Write a Python program to count the number of occurrences of a given element in a given list.

```python
def count_occurrences(lst, element_to_count):
    count = 0
    for item in lst:
        if item == element_to_count:
            count += 1
    return count


my_list = [1, 2, 3, 4, 2, 2, 5, 2, 6]
element = 2
result = count_occurrences(my_list, element)
print(f"The element {element} appears {result} times in the list.")
```

Output :

```python

The element 2 appears 4 times in the list.
```

In this program, we define a function `count_occurrences` that takes two arguments: `lst` (the list in which we want to count occurrences) and `element_to_count` (the element we want to count). We initialize a `count` variable to 0 and then iterate through the list, incrementing the `count` each time we find an element that matches the one we're counting. Finally, the function returns the count.

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**