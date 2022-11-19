# Lesson 0
## Preface
>Lesson and examples are stated in the "python" language. However, lesson objectives can be applied to othe languages with differing syntax.
&nbsp;
&nbsp;
> ### Lesson objectives
> Learn & Apply
>> 1. Basic built-in functions
>> 2. Comments
>> 3. Math operators

## Variables
``` python 
a = "Hello World"
```
> Variables are commonly used in programming. It is similar to algebra where a value is assigned to a name.



## Basic built-in functions
#### 1a. print()
```python 
print("Hello World")
```
### Output
``` terminal
> Hello World
```
> print() instructs the computer to generate the text within the paranthesis, as an output in its console/terminal.
> 
similarly, we can instruct the computer to generate a variable as an output.
``` python
a = "Hello World"
print(a)
```

### Output
``` terminal
> Hello World
```

#### 1b. input()
> input() prompts the user with a text. it then saves the user's response as a variable 
``` python 
a = input("What is your name?: ")
print (a)
```

### Output
``` terminal
> What is your name?: Andrew
> Andrew
```

## Commenting
> Commenting enables programmers to leave notes within the code, explaining its functions.
>
> The computer will ignore all text within the comments.

>Comments in python is demarcated by different insignias. 
>
> `"#"`  is used for single line commenting
> 
> while `'''` triple inverted commas are used at start and end of multi-line comments

```python 
#example

#this is single line comment

'''
this is 
multi-line
commenting.
'''
```

## Math Operators
> Programmers make use of mathematical logic  as well.
>
> However, operators insignias may vary depending on programming language. In our example, we show a few of python's mathematical operators.
```python
int a, b, i

# addition
i = a + b

#subtraction
i = a - b

# multiplication
i = a * b

# division
i = a / b

# floor division 
i = a // b

# modulus 
i = a % b

# in python, math library can also be called 
import Math

# ceiling division 
i = Math.ceil(a / b)

```
