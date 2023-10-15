---
title: "DAY 26 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Sun Oct 15 2023 18:03:54 GMT+0000 (Coordinated Universal Time)
cuid: clnrrzjux000009l34hmofqmn
slug: day-26-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1697390040763/6874a692-22d2-4a98-a201-2be3d2306fba.png
tags: python, python3, basics-of-python

---

## Write a Python program to find the common elements between three given lists:

```python
list1 = [1, 2, 3, 4, 5]
list2 = [3, 4, 5, 6, 7]
list3 = [5, 6, 7, 8, 9]
set1 = set(list1)
set2 = set(list2)
set3 = set(list3)
common_elements = set1.intersection(set2, set3)
common_elements_list = list(common_elements)
print("Common elements:", common_elements_list)
```

Output :

```python

Common elements: [5]
```

This Python program finds the common elements between three given lists: `list1`, `list2`, and `list3`. It does this by converting the lists into sets to efficiently handle duplicate elements, then uses the `intersection` method to find the common elements among the sets. The resulting common elements are stored in the `common_elements` set. If you need the result as a list, you can convert the `common_elements` set back into a list and store it in `common_elements_list`. Finally, the program prints the common elements found in the three lists.

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**