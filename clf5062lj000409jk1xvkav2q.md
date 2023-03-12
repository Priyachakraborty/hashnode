---
title: "Basics of  Python-6"
datePublished: Fri Mar 10 2023 06:16:21 GMT+0000 (Coordinated Universal Time)
cuid: clf5062lj000409jk1xvkav2q
slug: basics-of-python-day-6
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/84010ce9bffccdf3a6497b5d9f156f5b.jpeg
tags: python, datatypes, python-beginner, tuples, basics-of-python

---

# Day 6

## Tuple :

Tuple is an *in-built data* type in python and is used to collect objects, by separation of commas.

> 1. *Tuples are mutable.*
>     
> 2. *We use the '( )' operator to denote a tuple*
>     
> 3. Indexing is the same as the list
>     

Let's solve a few problems on tuples:

1. *Find the maximum and minimum element in the tuple* :
    

```python
n=(1,5,3,2,0)
print(sorted(n))
print(max(n))
print(min(n))
```

output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678600567025/076aeaba-5e1b-4fa1-885d-5257ebd65d33.png align="center")

1. *To find the sum of the tuple element*:
    

```python
n=(7,9,3,4)
sum=0
for i in n:
    sum=sum+i 
print(sum)
```

output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678600830453/33cbc898-a0e3-41b1-aa69-4c64703b9c19.png align="center")

**Problems** :

1. `Write a python program to find Row-wise element Addition in Tuple Matrix`
    
2. `Write a python program to update each element in the tuple list`
    
3. `Write a python program to multiply Adjacent elements`
    
4. `Write a python program to join Tuples if the similar initial element`
    
5. `Write a python program to find All pair combinations of 2 tuples`
    
6. `Write a python program to remove Tuples of Length K`
    
7. `Write a python program to remove Tuples from the List having every element as None`
    
8. `Write a python program to sort a list of tuples by the second Item`
    
9. `Write a python program to sort Tuples by Total digits`
    
10. `Write a python program to find Elements frequency in Tuple`
    
11. `Write a python program to filter Range Length Tuples`
    
12. `Write a python program to assign Frequency to Tuples`
    
13. `Write a python program to find Records with Value at the K index`
    

Let's have a look at the basic difference between `list` and `tuple` :

| LIST | TUPLE |
| --- | --- |
| we use '\[ \]' operator | we use '( )' operator |
| List is mutable | Tuple is immutable |

In my next blog, you will get to about set data types.

Thank you!