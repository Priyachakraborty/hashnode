---
title: "Basics of Python-11"
datePublished: Wed Mar 15 2023 16:33:32 GMT+0000 (Coordinated Universal Time)
cuid: clfcrevyj000r09jld94z5aax
slug: basics-of-python-day-11
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/bc40fb2f3c1ed794c434769dc1fe83aa.jpeg
tags: python, patterns, basics-of-python, for-loops

---

## Day-11

### Pattern printing :

Pattern printing is done by using loops in python. I am going to use `for loop` for pattern printing. By doing it, you will get a clear idea about loops in python, it makes you get a clear understanding to approach a problem.

1. Write a python program to print this pattern:-
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679056888777/5f7c8fad-611e-4ef6-bbf4-16836ee0303d.png align="center")
    
    ```python
    n=5
    i=1;j=0
    while(i<=n):
    	while(j<=i-1):
    		print("* ",end="")
    		j+=1
    	
    	print("\r")
    	j=0;i+=1
    ```
    
    output :
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679056955241/f79d6004-281d-4d78-9ac4-9255703a7e29.png align="center")

1. Write a python program to print this pattern:-
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679057068285/e4aaa7cc-cbb4-4e46-b2f8-ea962964a90f.png align="center")

```python
n = 5
for i in range(1, n+1):
    for j in range(n - i):
        print(' ', end='')
    for k in range(2 * i - 1):
        print('*', end='')
    print()
	
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679057129524/761eee98-def8-4282-8071-79941ed3d1c6.png align="center")

1. Write a python program to print this pattern:-
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679057239380/0ade0734-0280-4b6b-b5a6-c4e9b3bf7223.png align="center")

```python
size = 5
num = 1
for i in range(1, size + 1):
    for j in range(size, i - 1, -1):
        print(" ", end="")
    for k in range(0, i * 2 - 1):
        print(num, end="")
        num += 1
    num = 1
    print()
for i in range(1, size):
  for j in range(0, i+1):
        print(" ", end="")
 for k in range((size - i) * 2 - 1):
        print(num, end="")
        num += 1
   num = 1
   print()
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679057427433/2afd1fb8-0d46-4b0f-adc3-b65a0f526b5d.png align="center")

These are the basic pattern printing,by using for loop in python. In my next blog ,you will get to know about while loop in python.

Thank you !!