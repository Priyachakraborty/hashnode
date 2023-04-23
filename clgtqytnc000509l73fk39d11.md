---
title: "DAY 8 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Sun Apr 23 2023 18:32:57 GMT+0000 (Coordinated Universal Time)
cuid: clgtqytnc000509l73fk39d11
slug: day-8-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682272766761/4f36021b-ac63-4fb2-8580-3cc3df29ca25.png
tags: python, string, 100daysofcode, basics-of-python, day-8

---

# Write a Python program to count the number of vowels in a given string :

```python
vowels = set("aeiouAEIOU")
count = 0
string = input("Enter a string: ")
for char in string:
    if char in vowels:
        count += 1
print("The number of vowels in the string is:", count)
```

## Output :

```python
Enter a string: priya
The number of vowels in the string is: 2
```

* The program defines a set of vowels to check against. It uses the `set()` function to create a set of the characters "a", "e", "i", "o", and "u", as well as their uppercase equivalents.
    
* By creating a set, the program ensures that each character appears only once in the set, and it can check if a character is a vowel by using the `in` operator, which checks if an item is in a set in constant time.
    
* The program initializes a counter to zero. This counter will be used to keep track of the number of vowels in the string. The program prompts the user to enter a string by calling the built-in `input()` function.
    
* The user's input will be stored in the `string` variable. The program iterates over each character in the string by using for loop.
    
* For each character in the string, it checks if the character is in the set of vowels defined earlier. If the character is a vowel, the program increments the counter by 1. Finally, the program prints the final count of vowels in the string by using the `print()` function.
    
* The output will be a string that includes the message "The number of vowels in the string is:" followed by the value of the `count` variable.
    

---

If you are a beginner and want to know more about Python programming, you can read my [Basics of Python](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [part 1](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [part 15](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

* ---
    
    **HAPPY LEARNING !!!**