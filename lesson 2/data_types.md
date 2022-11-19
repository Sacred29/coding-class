# Data Types & Casting
## Recall Previous Lesson
In the previous lesson, we learnt that variables are mutable terms, which outputs its coressponding value when called.


## Data type
Variables are classified based on their data type. Differing data types are stored and manipulated differently.

E.g.
``` python 
# string data type 
a = '10'
b = '20'

c = a + b

# integer data type
d = 10
e = 20

f = d + e

print(c) # output: '1020'
print(f) # output: 30
```

In the example above, we see the difference between the addition of string vs. integer type.

> When we '+' strings together, it treats the variables as text, concatenating them together

> when we '+' integers together, the machine treats the variables as numeric values.


> # Data types:
>
>Text Type:	str
>
>Numeric Types:	int, float, complex
>
>Sequence Types:	list, tuple, range
>
>Mapping Type:	dict
>
>Set Types:	set, frozenset
>
>Boolean Type:	bool
>
>Binary Types:	bytes, bytearray, memoryview
>
>None Type:	NoneType


## Casting 
Casting refers to converting one data type to another data type.


``` python
# in this example, we cast variable a from string to int
a = '10' 

print(type(a)) # output: <class 'str'>

print(type(int(a))) # output: <class 'int'>

```

We change the variable's data type by using constructor functions.

>int() - constructs an integer number from an integer literal, a float literal (by removing all decimals), or a string literal (providing the string represents a whole number)

>float() - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)

>str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals

type() - prints datatype of variable.