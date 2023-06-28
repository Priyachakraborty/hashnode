---
title: "DAY 15 of PYTHON top 100 questions : from Basic to Advanced !!"
datePublished: Wed Jun 28 2023 19:24:41 GMT+0000 (Coordinated Universal Time)
cuid: cljg3vkjg000009md1reg38ij
slug: day-15-of-python-top-100-questions-from-basic-to-advanced
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1687957918812/3bab2d33-4894-4baf-9565-f446cfd6a0a3.png
tags: python, python3, basics, basics-of-python

---

# Write a Python program to print the Fibonacci series up to a given number:

```python
n = int(input("Enter the number: "))
n1, n2 = 0, 1
count = 0
if n <= 0:
    print("Please enter a positive integer.")
elif n == 1:
    print("Fibonacci sequence up to", n, "term(s):")
    print(n1)
else:
    print("Fibonacci sequence up to", n, "term(s):")
    while count < n:
        print(n1)
        nth = n1 + n2
        n1 = n2
        n2 = nth
        count += 1
```

Output :

```python
Enter the number: 6
Fibonacci sequence up to 6 term(s):
0
1
1
2
3
5
```

1. n = int(input("Enter the number: ")): The user is prompted to enter a number, which is stored in the variable n. This number represents the number of terms in the Fibonacci sequence that we want to generate.
    
2. n1, n2 = 0, 1: Two variables, n1 and n2, is initialized to 0 and 1 respectively. These variables represent the first two numbers of the Fibonacci sequence.
    
3. count = 0: A counter variable count is initialized to 0. This variable keeps track of the number of terms generated so far.
    
4. if n &lt;= 0: ... elif n == 1: ... else: ...: This conditional statement checks the value of n to handle different cases.
    
    * If n is less than or equal to 0, it means an invalid input was provided, so the program displays a message asking for a positive integer.
        
    * If n is equal to 1, it means we only want to generate the first term of the Fibonacci sequence. In this case, the program prints the value of n1 (which is 0) as the only term.
        
    * For any other value of n, the program proceeds to generate the Fibonacci sequence using a loop.
        
5. while count &lt; n: ...: This while loop continues until the count reaches the desired number of terms (n).
    
6. print(n1): The current term (n1) is printed.
    
7. nth = n1 + n2: The next term of the Fibonacci sequence is calculated by adding n1 and n2, and it is stored in the variable nth.
    
8. n1 = n2 and n2 = nth: The values of n1 and n2 are updated for the next iteration of the loop. n1 takes the value of n2, and n2 takes the value of nth.
    
9. count += 1: The counter count is incremented by 1 to keep track of the number of terms generated so far.
    
10. After the loop ends, the program has generated the Fibonacci sequence up to the desired number of terms, and it prints each term one by one.
    

---

If you are a beginner and want to know more about Python programming, you can read my [**Basics of Python**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) blogs (From [**part 1**](https://hashnode.com/post/cleuwavnj008gurnv4fc650hh) to [**part 15**](https://hashnode.com/post/clff4058101hng5nvefv85yzt)).

---

**HAPPY LEARNING !!!**