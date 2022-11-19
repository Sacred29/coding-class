# Lesson 3 - conditional statements
## Preface
>Lesson and examples are stated in the "python" language. However, lesson objectives can be applied to othe languages with differing syntax.
&nbsp;
&nbsp;


> ### Lesson objectives
> Learn & Apply
>> 1. "If Else" Statements


&nbsp;

&nbsp;
## 1. "If Else" Statements
>If-Else statements are aka (also known as) conditional statements. 
>
>A specific set of instructions are perfomed if a condition is met.

&nbsp;

If-Else statements have 3 main keywords:
> 1. if  
> 2. else
> 3. elif (means else if)



## if condition
```python
#example code.

#prompts user for their age, saves it under variable "myAge" (as data type integer). 
myAge = int(input("please input your age:"))

#if their age exceeds 60, the computer is instructed to mock user.
if(myAge > 60):
    print("You are old.")
```
### Output
``` terminal 
#first run
> please input your age:61
> You are old.

#second run
> please input your age:60
>
```

>In the example, if the user's age meets the condition of above 60, 
>the instruction to mock user is perfomed.
>
>However, it returns nothing when it does not meet the condition.


>We use the "else" condition to overcome this

> **Key Points 💡**
> 
> 1. All "if-else" statements starts with "if"




## else condition

```python
#example code.

#prompts user for their age, saves it under variable "myAge" (as data type integer). 
myAge = int(input("please input your age:"))

#if their age exceeds 60, the computer is instructed to mock user.
if(myAge > 60):
    print("You are old.")
#else, the computer congratulates the user for their youth
else:
    print("You are young.")
```
### Output
``` terminal 
#first run
> please input your age:61
> You are old.

#second run
> please input your age:60
> You are young.
```

>In the example, we can see that if user's age is under 60, it congratulates for their youth.
>
> However, "if" and "else" are not sufficient for more than 1 condition.

> **Key Points 💡**
> 
> 1. else will run when its previous condition fails
> 2. else has to be after an "if" condition.
> 3. else can only occur once, at most, within a single "if" condition. 


# elif condition
> elif means "else if" enables a secondary condition, if the first condition is false.
```python
#example code.

#prompts user for their age, saves it under variable "myAge" (as data type integer). 
myAge = int(input("please input your age:"))

#if their age exceeds 60, the computer is instructed to mock user.
if(myAge > 60):
    print("You are old.")
#if their age is within the range includive of 31 to 60.
elif(30> myAge >=60):
    print("you are in your prime")
elif(61> myAge >=80):
    print('older')
else:
    print("You are young.")
```
### Output
``` terminal 
#first run
> please input your age:61
> You are old.

#second run
> please input your age:60
> You are in your prime.

#third run 
> please input your age:30
> You are young.
```
> **Key Points 💡**
> 
> 1. elif will run when its previous condition fails
> 2. elif has to be after an "if" condition.
> 3. there can be multiple occurances in a single if statement. 



# Challenge
>Create a classification system for our bmi calculator.
>
>>Classifications are as such :
>>- If your BMI is less than 18.5, it falls within the underweight range.
>>- If your BMI is 18.5 to <25, it falls within the healthy weight range.
>>- If your BMI is 25.0 to <30, it falls within the overweight range.
>>- If your BMI is 30.0 or higher, it falls within the obesity range.