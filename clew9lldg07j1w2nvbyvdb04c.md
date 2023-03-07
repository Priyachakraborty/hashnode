---
title: "Basics Of Python -2"
datePublished: Mon Mar 06 2023 03:30:40 GMT+0000 (Coordinated Universal Time)
cuid: clew9lldg07j1w2nvbyvdb04c
slug: basics-of-python-2
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/4c3d4117927d9cb1f0f6d57f85aeb37d.jpeg
tags: python, basics, datatypes, python-beginner, day2

---

## **DAY 2:**

*In this blog, you will get to know about the basic data types of python.*

<details data-node-type="hn-details-summary"><summary>DATA TYPES</summary><div data-type="detailsContent">Data types are nothing but the classification of the data items in python. Like by using data types, we get to know about the class of that particular data.</div></details>

There are different types of in-built data types in python. We will discuss it with examples.

**<mark>DATA TYPES IN PYTHON</mark>**<mark>:</mark>

1. Numeric
    
2. Boolean
    
3. Sequential
    
4. Dictionary
    
5. Set
    

1. ## Numeric -
    

*Numeric data types in python define a numerical class.*

* Integer
    
* Float
    
* Complex
    

**<mark>Integer</mark>**

```python
n=45
print(type(n))
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678019643882/bb2ffac8-0195-4e08-9dcc-e241a0493a9d.png align="center")

**<mark>Float</mark>**

```python
n=5.01
print(type(n))
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678019750137/62e75724-2a80-46f3-8911-108b0051ac89.png align="center")

**<mark>Complex</mark>**

```python
n=5.01+1j
print(type(n))
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678019828009/d734ac1b-82ac-41d1-8be9-c35dce75c140.png align="center")

These are the numeric data types in python.

---

1. ## Boolean
    

*Boolean data types are whether the object is true or false.*

```python
print(type(True))
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678021151289/dd70e17d-afc2-471c-9847-ce1a81cbf630.png align="center")

```python
print(type(False))
```

output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678021195935/343eb5ed-8fc5-40de-b07b-58c0a3acc87f.png align="center")

It is very important, to write the first letter of "True" in capital "T", and "False" in capital "F", otherwise you may get an error.

1. ## Sequential
    

*Sequential data types are the ordered collection of data items.*

* String
    
* List
    
* Tuple
    

---

**<mark>String</mark>**

* Collection of characters
    

```python
s=str(input("Enter the name : "))
print(s)
print(type(s))
```

output :

```python
Enter the name : Priya
Priya
<class 'str'>
```

**<mark>List</mark>**

* Collection of data
    

```python
l=[2,4,5,2]
print(l)
print(type(l))
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678034872061/31d5cab1-2244-4cb4-8e17-b4d40b540f31.png align="center")

**<mark>Tuple</mark>**

* ordered collection of data
    

```python
t=(4,6,2,4)
print(t)
print(type(t))
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678035042927/a3a77500-d16b-49e7-b582-b9c3de16337a.png align="center")

---

1. ## Dictionary
    

* *An unordered collection of data has a "Key" and "Value", the key is immutable whereas the value is mutable.*
    

```python
l={1:'Me',2:'You',3:'Us'}
print(l)
print(type(l))
```

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678035760399/5d6c11d3-4e12-4388-90f0-18fdc067e0bf.png align="center")

---

1. ## Set
    

* *The set is an unordered collection of data that is mutable, iterable and has no duplicate items.*
    
    ```python
    l={2,3,4,2,3,6,7,8,4}
    print(l)
    print(type(l)) 
    ```
    

output :

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1678036093684/fdda29d3-aacd-4808-9931-ad8ac0d664a5.png align="center")

These are the data types ,or in-built data types of python programming.

*For your reference* :

| DATA TYPES | IMMUTABLE | MUTABLE |
| --- | --- | --- |
| Numeric | ✅ | ❌ |
| List | ❌ | ✅ |
| String | ✅ | ❌ |
| Dictionary | ❌ | ✅ |
| Tuple | ✅ | ❌ |
| Set | ❌ | ✅ |

In my next blog ,you will get to know more about this data types in details.

Thank you.