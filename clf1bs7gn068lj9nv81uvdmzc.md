---
title: "Basics of Python-5"
datePublished: Thu Mar 09 2023 16:30:39 GMT+0000 (Coordinated Universal Time)
cuid: clf1bs7gn068lj9nv81uvdmzc
slug: basics-of-python-5
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/5df2c9d757f6ce24b7b0394774fe8c7e.jpeg
tags: python, string, datatypes, basics-of-python, day5

---

## Day 5

### String :

The string is an in-built data structure in python, which is an **immutable data type**, that is a *sequential collection of characters*.

Because String is an immutable data type so we cannot change the string after it's written.

Let's solve a few problems on String :

1. Write a python program to check whether the string is palindrome or not
    

`Logic: You have to check whether the word, you are reading from forward is the same as you are reading from backward.`

```python
s=str(input("Enter your String : "))
if s[::-1] == s:
    print("String is Palindrome")
else:
    print("String is not Palindrome")
```

Output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678350939430/3cce6de3-b79f-4009-bbcb-02242296564d.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678351008616/705366c4-7595-4e9e-b6b4-847776fbfe79.png align="center")

1. Write a python program to join and split a string
    

`Logic: First you have to split a string and join it through '-'`

```python
n='BASICS OF PYTHON'
print(n.split(" "))
print('-'.join(n.split()))
```

Output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678377179583/299c14aa-45ed-427f-a99e-081d835eb60f.png align="center")

Here are a few problems on String :

1. *Write a python program to find Reverse words in a given String in Python*
    
2. *Write a python program to remove i’th character from a string in Python*
    
3. *Write a python program to avoid Spaces in string length*
    
4. *Write a python program to print even-length words in a string*
    
5. *Write a python program to uppercase Half String*
    
6. *Write a python program to capitalize the first and last character of each word in a string*
    
7. *Write a python program to check if a string has at least one letter and one number*
    
8. *Write a python program to accept the strings which contain all vowels*
    
9. *Write a python program to count the number of vowels using sets in a given string*
    
10. *Write a python program to remove all duplicates from a given string*
    
11. *Write a python program to check the Least Frequent Character in a String*
    
12. *Write a python program to find Odd Frequency Characters*
    
13. *Write a python program to a specific Characters Frequency in the String List*
    
14. *Write a python program to check the Frequency of numbers in a String*
    
15. *Write a python program to check if a string contains any special character*
    
16. *Write a python program to generate random strings until a given string is generated*
    
17. *Write a python program to find words that are greater than the given length of k*
    
18. *Write a python program to remove i-th character from a string*
    
19. *Write a python program to find the length of a string in python*
    
20. *Write a python program to count the number of matching characters in a pair of string*
    
21. *Write a python program to check the Maximum frequency character in the String*
    

In my next blog,you will get to know about tuples data type.

Thank you.