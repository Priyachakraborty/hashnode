---
title: "Basics of Python-8"
datePublished: Sun Mar 12 2023 14:48:46 GMT+0000 (Coordinated Universal Time)
cuid: clf6xwpgr000d09lbeovfaxs5
slug: basics-of-python-8
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/ccfa53489930bcfd0e1559b791f18c29.jpeg
tags: python, dictionary, python-beginner, basics-of-python, python-dictionaries

---

## Day 8

### Dictionary :

*An unordered collection of data types that has a "Key" and "Value".*

***The key is immutable whereas the value is mutable.***

Let's solve a problem :

1. Write a python program to sort a dictionary based on keys.
    

```python
from collections import OrderedDict

dict={'Me':10,'you':1,'us':34}
y=list(dict.keys())

#this will sort on the basis of key
x=OrderedDict(sorted(dict.items()))
print(x)
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678718285389/51003e21-52d8-4399-8724-6969c533f07b.png align="center")

*More Problems :*

`Write a python program to Sort Python Dictionaries by Key or Value`

`Write a python program to Handle missing keys in Python dictionaries`

`Write a python program to find the sum of all items in a dictionary`

`Write a python program to find the size of a Dictionary`

`Write a python program to Merge two Dictionaries`

`Write a python program to create a grade calculator in Python`

`Write a python program to Check the order of characters in a string using OrderedDict( )`

`Write a python program to Find common elements in three sorted arrays by dictionary intersection`

`Write a python program to Find all duplicate characters in a string`

`Write a python program to Replace String with Kth Dictionary value`

`Write a python program to remove a key from the dictionary`

`Write a python program to Replace words from the Dictionary`

`Write a python program to Remove Dictionary Key Words`

---

In my next blog, you will get to know about loops in python.

Thank you!