---
title: "🐍Python - ZerO to HerO (BASIC Knowledge)"
seoTitle: "Python Programming"
datePublished: Mon May 01 2023 08:18:39 GMT+0000 (Coordinated Universal Time)
cuid: clh4kjniv000009mh32snc0py
slug: python-zero-to-hero-basic-knowledge
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/cxMJYcuCLEA/upload/d17e98ab2e49d34fa7acbe94c987bb03.jpeg
tags: programming-blogs, python3, coding, python-beginner, basics-of-python

---

# 🐍What is Python Programming?

Python is a high-level, interpreted programming language that is known for its simplicity, readability, and ease of use. It was created by Guido van Rossum and first released in 1991.

Python is an open-source language that can be used for a variety of purposes, including web development, data analysis, machine learning, scientific computing, and more. It has a large and active community of developers who contribute to its development and maintenance.

Python's syntax is straightforward to learn, making it an excellent language for beginners. It supports multiple programming paradigms, including procedural, functional, and object-oriented programming. It also has a vast standard library that provides a wide range of built-in functions and modules for various tasks, such as working with files, networking, and data manipulation.

Python's popularity has grown rapidly in recent years due to its versatility, readability, and ease of use, as well as the increasing demand for data science and machine learning.

## 🐍Why is it necessary to learn?

* Versatility: Python is a versatile language that can be used for a wide range of applications, including web development, data analysis, machine learning, scientific computing, and more. Learning Python can open up many opportunities for you in various fields.
    
* In-demand skill: Python is one of the most popular programming languages in the world, and its demand is only increasing. Many companies are looking for professionals who have Python skills, especially in the fields of data science and machine learning.
    
* Easy to learn: Python has a straightforward and easy-to-learn syntax that makes it an excellent language for beginners. You can quickly get started with Python and start building your programs.
    
* Large community: Python has a vast and active community of developers who contribute to its development and maintenance. You can find a wealth of resources, such as tutorials, documentation, and forums, to help you learn Python.
    
* Open-source: Python is an open-source language, which means that you can use it freely and contribute to its development. This makes it an excellent language for collaborative projects and learning from others.
    

---

📌Let's Start with the Basics of Python :

### Topics :

1. *Basic Print Statement*
    
2. *Data Types*
    
3. *Conditional Statements*
    
4. *List, String, tuple, Set, Dictionary*
    
5. *Loops*
    
6. *Function*
    
7. *OOPs(Basic Concept)*
    

---

## 🐍Print Statement :

In Python, the print statement is used to display the output of a program. It can be used to print strings, numbers, variables, and expressions.

```python
print('Hello Reader !')
```

```plaintext
OUTPUT :

Hello Reader !
```

---

## 🐍Data Types :

Python has several built-in data types that can be used to represent different kinds of values. Here are some of the most common data types in Python:

1. **Numeric Types:**
    
    * **int**: integers
        
    * **float**: floating-point numbers
        
    * **complex**: complex numbers
        
2. **Boolean Type:**
    
    * **bool**: Boolean values (True or False)
        
3. **Sequence Types:**
    
    * **str**: strings
        
    * **list**: lists
        
    * **tuple**: tuples
        
4. **Mapping Type:**
    
    * **dict**: dictionaries
        
5. **Set Types:**
    
    * **set**: sets
        

<table><tbody><tr><td colspan="1" rowspan="1"><p><strong>DATA TYPES</strong></p></td><td colspan="1" rowspan="1"><p><strong>IMMUTABLE</strong></p></td><td colspan="1" rowspan="1"><p><strong>MUTABLE</strong></p></td></tr><tr><td colspan="1" rowspan="1"><p>Numeric</p></td><td colspan="1" rowspan="1"><p>✅</p></td><td colspan="1" rowspan="1"><p>❌</p></td></tr><tr><td colspan="1" rowspan="1"><p>List</p></td><td colspan="1" rowspan="1"><p>❌</p></td><td colspan="1" rowspan="1"><p>✅</p></td></tr><tr><td colspan="1" rowspan="1"><p>String</p></td><td colspan="1" rowspan="1"><p>✅</p></td><td colspan="1" rowspan="1"><p>❌</p></td></tr><tr><td colspan="1" rowspan="1"><p>Dictionary</p></td><td colspan="1" rowspan="1"><p>❌</p></td><td colspan="1" rowspan="1"><p>✅</p></td></tr><tr><td colspan="1" rowspan="1"><p>Tuple</p></td><td colspan="1" rowspan="1"><p>✅</p></td><td colspan="1" rowspan="1"><p>❌</p></td></tr><tr><td colspan="1" rowspan="1"><p>Set</p></td><td colspan="1" rowspan="1"><p>❌</p></td><td colspan="1" rowspan="1"><p>✅</p></td></tr></tbody></table>

---

## 🐍Conditional Statements:

In Python, conditional statements are used to control the flow of a program based on certain conditions.

*The if statement checks if a condition is True, and if it is, the code inside the if block is executed. If the condition is False, the program moves on to the elif statement (if there is one), which allows for additional conditions to be checked. If the condition in the elif statement is True, the code inside the elif block is executed. If the condition is False, the program moves on to the else statement (if there is one), which is a catch-all that is executed if all the previous conditions are False.*

```python
x = 30

if x < 0:
    print("x is negative")
elif x == 0:
    print("x is zero")
else:
    print("x is positive")
```

```python
OUTPUT:

X is positive
```

---

## 🐍List, String, tuple, Set, Dictionary :

### 📌List:

An ordered, mutable collection of values. Lists are denoted by square brackets \[\].

```python
fruits = ["apple", "banana", "cherry"] 
print(fruits) 
```

```python
 Output: 
['apple', 'banana', 'cherry']
```

### 📌String:

A sequence of characters. Strings are denoted by either single or double quotes (' or ") and are immutable.

```python
greeting = "Hello, world!" 
print(greeting) 
```

```python
Output: 
Hello, world!
```

### 📌Tuple:

An ordered, immutable collection of values. Tuples are denoted by parentheses ().

```python
coordinates = (10, 20) 
print(coordinates) 
```

```python
Output: 
(10, 20)
```

### 📌Set:

An unordered collection of unique values. Sets are denoted by curly braces {} or by using the set() function.

```python
numbers = {1, 2, 3, 4, 5} 
print(numbers) 
```

```python
 Output: 
{1, 2, 3, 4, 5}
```

### 📌Dictionary:

An unordered collection of key-value pairs. Dictionaries are denoted by curly braces {} and each key-value pair is separated by a colon ':'.

```python
person = {"name": "Alice", "age": 30} 
print(person) 
```

```python
Output: 
{'name': 'Alice', 'age': 30}
```

---

## 🐍Loops:

In Python, there are two main types of loops: for loops and while loops.

A for loop is used to iterate over a sequence of values, such as a list or a string.

```python
fruits = ["apple", "banana", "cherry"] 
for fruit in fruits:
    print(fruit)
```

```python
Output:

apple
banana
cherry
```

A while loop is used to repeatedly execute a block of code as long as a certain condition is True. The basic syntax of a while loop is:

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

```python
Output:
0
1
2
3
4
```

Loops are important constructs in programming as they allow you to repeat code without having to write it out manually for each iteration.

---

## 🐍Function:

In Python, a function is a block of reusable code that performs a specific task. Functions allow you to break your code into smaller, more manageable pieces and can make your code more modular and easier to read.

Here's an example of a function that takes two numbers as input and returns their sum:

```python
def add_numbers(num1, num2):
    sum = num1 + num2
    return sum

x = 3
y = 5
result = add_numbers(x, y)
print(f"The sum of {x} and {y} is {result}")

```

```python
Output:
The sum of 3 and 5 is 8
```

---

## 🐍OOPs(Basic Concept)

Object-Oriented Programming (OOP) is a programming paradigm that emphasizes the concept of objects, which can contain data and code that operates on that data. Python is an object-oriented language, which means it provides support for OOP concepts such as encapsulation, inheritance, and polymorphism.

Here's an example of a simple class definition in Python:

```python
class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year

    def start(self):
        print("The car is starting...")

    def stop(self):
        print("The car is stopping...")

my_car = Car("Toyota", "Camry", 2020)
print(my_car.make)  
print(my_car.model) 
print(my_car.year)  
my_car.start()      
my_car.stop()       
```

```python
Output: 

Toyota
Camry
2020
The car is starting...
The car is stopping...
```

---

## 🐍TOP QUESTIONS FOR BASICS OF PYTHON :

🔍Write a Python program that accepts a number from the user and determines whether it is even or odd.

🔍Write a Python program to find the sum of all numbers between 1 and a given number.

🔍Write a Python program to find the largest element in an array.

🔍Write a Python program to find the second largest element in an array.

🔍Write a Python program to reverse a given string.

🔍Write a Python program to find the factorial of a given number.

🔍Write a Python program to check whether a given string is a palindrome or not.

🔍Write a Python program to count the number of vowels in a given string.

🔍Write a Python program to check whether a given number is a prime number or not.

🔍Write a Python program to sort a given array in ascending order.

🔍Write a Python program to check whether a given number is a palindrome or not.

🔍Write a Python program to find the first N prime numbers.

🔍Write a Python program to find the sum of all even numbers between 1 and a given number.

🔍Write a Python program to find the sum of all odd numbers between 1 and a given number.

🔍Write a Python program to calculate the area and circumference of a circle with a given radius.

🔍Write a Python program to convert a given binary number to decimal.

🔍Write a Python program to find the greatest common divisor (GCD) of two numbers.

🔍Write a Python program to print the Fibonacci series up to a given number.

🔍Write a Python program to reverse a given list.

🔍Write a Python program to find the number of occurrences of a given element in a list.

🔍Write a Python program to find the sum of all elements in an array.

🔍Write a Python program to find the product of all elements in an array.

🔍Write a Python program to find the largest and smallest element in an array.

🔍Write a Python program to find the missing number in a given array of integers.

🔍Write a Python program to remove duplicates from a given list.

🔍Write a Python program to count the number of words in a given string.

🔍Write a Python program to check whether two strings are anagrams or not.

🔍Write a Python program to find the length of the longest substring without repeating characters in a given string.

🔍Write a Python program to find the median of a given list of numbers.

🔍Write a Python program to check whether a given string is a pangram or not.

🔍Write a Python program to sort a given list of integers in descending order.

🔍Write a Python program to find the sum of the digits of a given number.

🔍Write a Python program to find the length of the longest increasing subsequence of a given list of integers.

🔍Write a Python program to find the common elements between two given lists.

🔍Write a Python program to find the second smallest element in a given list.

🔍Write a Python program to find the sum of all elements in a given matrix.

🔍Write a Python program to find the transpose of a given matrix.

🔍Write a Python program to check whether a given number is a perfect number or not.

🔍Write a Python program to find the ASCII value of a given character.

🔍Write a Python program to find the area of a triangle given its base and height.

🔍Write a Python program to find the common elements between three given lists.

🔍Write a Python program to reverse a given integer number.

🔍Write a Python program to find the length of the longest palindrome substring in a given string.

🔍Write a Python program to find the second-largest element in a given dictionary.

🔍Write a Python program to find the sum of all prime numbers between two given numbers.

🔍Write a Python program to check whether a given year is a leap year or not.

🔍Write a Python program to find the sum of all elements in a given set.

🔍Write a Python program to check whether a given number is an Armstrong number or not.

🔍Write a Python program to find the factorial of a given number using recursion.

🔍Write a Python program to find the median of a given list of numbers without using the built-in function.

🔍Write a Python program to find the sum of all elements in a given tuple.

🔍Write a Python program to find the first non-repeating character in a given string.

🔍Write a Python program to find the number of vowels and consonants in a given string.

🔍Write a Python program to find the sum of all elements in a given dictionary.

🔍Write a Python program to find the number of words that start with a vowel in a given string.

🔍Write a Python program to check whether a given string is a palindrome or not without using the built-in function.

🔍Write a Python program to find the sum of all elements in a given nested list.

🔍Write a Python program to check whether a given number is a perfect square or not.

🔍Write a Python program to generate all possible permutations of a given string.

🔍Write a Python program to find the sum of all elements in a given two-dimensional array.

🔍Write a Python program to find the maximum and minimum values in a given list of tuples.

🔍Write a Python program to find the first duplicate element in a given array.

🔍Write a Python program to count the number of occurrences of a given element in a given list.

🔍Write a Python program to find the largest palindrome made from the product of two n-digit numbers.

🔍Write a Python program to check whether a given string is a substring of another given string.

🔍Write a Python program to find the sum of all even numbers in a given list.

🔍Write a Python program to find the maximum occurring character in a given string.

🔍Write a Python program to find the number of even and odd elements in a given list.

🔍Write a Python program to find the area of a circle given its radius.

🔍Write a Python program to find the sum of the first n prime numbers.

---

☑️If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

1. [***Basics of Python***](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh)***\-1 -*** `Print Statement`
    
2. [***Basics of Python-2***](https://hashnode.com/post/clew9lldg07j1w2nvbyvdb04c) ***-*** `Data Types`
    
3. [***Basics of Python-3***](https://hashnode.com/post/clexp1f7800u8wunv6l8xczlm) ***-*** `Conditional Statement`
    
4. [***Basics of Python-4***](https://hashnode.com/post/clezyhiwt02fcljnv8pfb7tti) ***-*** `List`
    
5. [***Basics of Python-5***](https://hashnode.com/post/clf1bs7gn068lj9nv81uvdmzc) ***-***`String`
    
6. [***Basics of Python-6***](https://hashnode.com/post/clf5062lj000409jk1xvkav2q) ***-*** `Tuple`
    
7. [***Basics of Python-7***](https://hashnode.com/post/clf53mky800080alc62ks4a8z) ***-*** `Set`
    
8. [***Basics of Python-8***](https://hashnode.com/post/clf6xwpgr000d09lbeovfaxs5) ***-*** `Dictionary`
    
9. [***Basics of Python-9***](https://hashnode.com/post/clf8kd97700030alfboczd5s8) ***-*** `Loops`
    
10. [***Basics of Python-10***](https://hashnode.com/post/clf9fo7bf000909l57gv8hd5j) ***-***`For loop`
    
11. [***Basics of Python-11***](https://hashnode.com/post/clfcrevyj000r09jld94z5aax) ***-*** `Pattern Printing`
    
12. [***Basics of Python-12***](https://hashnode.com/post/clfcrgpr4000909mh9wqqdf6f) ***-*** `While Loop`
    
13. [***Basics of Python-13***](https://hashnode.com/post/clfctwwt5013fwxnvbdlgeyg0) ***-***`Function`
    
14. [***Basics of Python-14***](https://hashnode.com/post/clff2lk1g00000al2cx924477) ***-*** `OOPs Concept`
    

Here you will get to know in detail about the topic I have discussed earlier.

---

### HAPPY LEARNING !🤍