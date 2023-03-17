---
title: "Basics of Python-13"
datePublished: Fri Mar 17 2023 17:43:39 GMT+0000 (Coordinated Universal Time)
cuid: clfctwwt5013fwxnvbdlgeyg0
slug: basics-of-python-13
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/f6f37465e81cddaa4f2973e3f56dd558.jpeg
tags: functions, python, basics-of-python, python-functions, types-of-functions

---

## Day-13

### Function :

Python function is a block of code to make the code easier and to do the specific task.

there are two types of functions in python -:

> 1. Built-in function
>     
> 2. User-defined function
>     

Basics syntax of function :

> def function\_name(parameter):
> 
> statement
> 
> return expression

### Built-in Functions in python:-

This type of function in python comes along with python software automatically.

some examples of built-in functions are :

> 1. `print()` - used to print values to the console
>     
> 2. `len()` - used to get the length of a string, list, tuple, dictionary, or set
>     
> 3. `type()` - used to get the type of a variable
>     
> 4. `input()` - used to get user input from the console
>     
> 5. `int()` - used to convert a string or float to an integer
>     
> 6. `float()` - used to convert a string or integer to a float
>     
> 7. `str()` - used to convert a variable to a string
>     
> 8. `range()` - used to generate a range of numbers
>     
> 9. `list()` - used to convert a sequence (e.g. a tuple) to a list
>     
> 10. `max()` - used to get the maximum value in a sequence.
>     

### User-defined Functions in python :

User-defined functions can be developed on their own.

An example of a user-defined function is:

> 1. Function to add two numbers:
>     
> 
> def add\_numbers(x, y):
> 
> return x + y
> 
> the basic syntax is :
> 
> `def function_name(parameter):`

Let's solve a few problems on function:

1. Write a python program to find odd and even numbers by using functions in python -
    

```python
def is_even(num):
    if num % 2 == 0:
        return True
    else:
        return False
n = int(input("Enter a number: "))
if is_even(n):
    print(n, "is even")
else:
    print(n, "is odd")
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679073447530/ada43cf9-0c1f-478b-bc1f-53aa087ada66.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679073472228/c086f635-d84b-4da5-8e41-ac397ab74399.png align="center")

1. Write a python program to print a calculator program by using the python function -
    

```python
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Cannot divide by zero"
    else:
        return x / y


num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")
choice = input("Enter choice (1/2/3/4): ")
if choice == '1':
    print(num1, "+", num2, "=", add(num1, num2))

elif choice == '2':
    print(num1, "-", num2, "=", subtract(num1, num2))

elif choice == '3':
    print(num1, "*", num2, "=", multiply(num1, num2))

elif choice == '4':
    print(num1, "/", num2, "=", divide(num1, num2))

else:
    print("Invalid input")
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679074040127/efdf31eb-6468-4ac3-b71b-7098838cc9f8.png align="center")

More problems :

1. `Write a function to find the maximum of three numbers`
    
2. `Write a function to check if a given year is a leap year`
    
3. `Write a function to compute the factorial of a given number`
    
4. `Write a function to reverse a string`
    
5. `Write a function to check if a given string is a palindrome`
    

In my next blog, you will get to know about the oops concept in python.

Thank you !!