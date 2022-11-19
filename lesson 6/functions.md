# Lesson 5 - Loops  
## Preface
>Lesson and examples are stated in the "python" language. However, lesson objectives can be applied to othe languages with differing syntax.
&nbsp;
&nbsp;

> ### Lesson objectives
> Learn & Apply
>> 1. Use of functions
>> 
## Functions
Functions are used to reduce code repetition. 

Rather than writing it out multiple times, Code is broken down into its functional purposes. It can be called at different points of the code with differing arguments.

>#### Arguments
>Information can be passed into functions as arguments.
>
>Arguments are specified after the function name, inside the parentheses. You can add as many arguments as you want, just separate them with a comma.
```python 
# def is short for define. In python, it is how a function is created.

# multiply is the function's name. This is arbitary, but must be unique as it is used as the reference, when calling a function.

# a and b are the arguments, they are dynamic in nature, which enables differing information to be parsed.

# A function is able to return data as well, in this case, a*b.
def multiply(a,b):
    return a * b

print(multiply(1,2)) # output: 2
print(multiply(3,4)) # output: 12
```

#
a function may not require arguments.

an example:

```python
def hii():
    print("hello world")
hii() # output: "hello world"
```