---
title: "Basics of Python-10"
datePublished: Tue Mar 14 2023 08:41:31 GMT+0000 (Coordinated Universal Time)
cuid: clf9fo7bf000909l57gv8hd5j
slug: basics-of-python-day-10
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/36c64037b0fd0960e2c6cf3c8f2a0b2f.jpeg
tags: python, loops, basics-of-python, for-loops, loops-in-python

---

## Day -10

### For Loop :

*For loop is used* ***to iterate a sequence of data items.***

let's solve some examples:

1. *Write a python program to find the factorial of a number :*
    

```python
n=int(input("Enter the number - "))
m=1
for i in range(1,n+1):
    m=m*i 
print("The factorial of number is -",m)
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678867903398/e326f1a8-ef9b-4c35-b0a4-129349e9789a.png align="center")

---

1. *Write a python program to print the sum of the digit of a number in the range*.
    

```python
n=int(input("enter the number "))
m=int(input("Enter second number"))
sum=0
for i in range(n,m+1):
    sum=sum+i 
print(sum)
```

output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678868471602/7e253ed0-4fd3-434c-bd7a-9528bef2b6f0.png align="center")

---

1. *Write a program to print the multiplication table of 7*
    

```python
n=int(input("Enter the number :"))
for i in range(1,11):
    print(n,"*",i,"=",n*i)
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678869061444/b63d8c9c-7754-4508-94d3-4152208c6a38.png align="center")

---

*More problems on for loop* :

`Write a program to convert temperature in Fahrenheit to centigrade.`

`Write a program to reverse a number`

`Write a program to print the following patterns` -

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678869351936/b0a603d8-6d3a-4a68-b645-bf7e1bc39f9e.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678869373475/a87c69db-f05f-4103-abb4-23832f26379a.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678869398644/28d4e388-9cd9-45b1-adfc-49e7603d5c5b.png align="center")

In my next blog, You will get to know! How to write a program to solve patterns by using for loop.

Thank you !!