# Lesson 5 - Loops  
## Preface
>Lesson and examples are stated in the "python" language. However, lesson objectives can be applied to othe languages with differing syntax.
&nbsp;
&nbsp;

> ### Lesson objectives
> Learn & Apply
>> 1. while loops
>> 2. for loops
>> 3. break
>> 4. continue
>> 5. else
>> 6. for loop range
>> 7. nested loops
>> 8. pass 


## While loop
with while loop, we can execute a set of statements, as long as the condition remains true.

``` python
i = 1
while i < 6:
  print(i)
  i += 1

```
#
### Output:
``` console
> 1
> 2
> 3
> 4
> 5
```

## For Loops
For loops are used to iterate over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

``` python 
names = ["andrew", "evan", "cheryl"]
for i in names:
    print(i)

```
#
### Output:
``` console
> andrew
> evan
> cheryl
```

## Break 
Break can stop the loop, even if the condition is true.

The Break statement can be used in both while and for loops

``` python 
i = 0
while i < 6:
    i += 1
    if (i == 3):
        break
    print(i)

```

``` console
> 1
> 2
```

## continue
The continue statement stops the current iteration and continues with the next.


The continue statement can be used in both while and for loops
``` python
i = 0
while i < 6:
    i += 1
    if (i == 3):
        continue
    print(i)
    
```

``` console
> 1
> 2
> 4
> 5
> 6
```
#
## Else
The else statement runs when the condition is no longer true. 

The else statement can be used in both while and for loops

``` python
i = 1
while i < 6:
    print(i)
    i += 1
else:
    print("i is no longer less than 6")

```
# 
### Output:

``` console 

> 1
> 2
> 3
> 4
> 5
> i is no longer less than 6
```

#
### Range function
The range function is used to loop through a set of code for a specified number of times.

The for-range loop function can accept up to 3 parameters. 
>
> range(starting index {optional; default 0}, ending index, increment value {optional; default 1})
>
> The range function  will start at the starting index (default 0), increase by increment (default 1), up till not inclusive of ending index.

``` python 
for x in range(6):
    print (x)
```

### output
``` console
> 0
> 1
> 2
> 3
> 4
> 5
```

When there are 2 paramenters, it is assumed that the first value is the starting index, and the latter value is the (not inclusive of) ending index.

``` python 
for x in range(2,6):
    print(x)
```
### output
``` console
> 2
> 3
> 4
> 5
```


When there are 3 parameters, the third parameter is to be the increment value

``` python
for x in range(2, 6, 2):
    print(x)

```
### output
``` console
> 2
> 4
```

#
## Nested loops
A nested loop is a loop within another loop.

>The "inner loop" will be executed one time for each iteration of the "outer loop":

``` python
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
    for y in fruits:
        print(x, y)
```
### output
``` console
> red apple
> red banana
> red cherry
> big apple
> big banana
> big cherry
> tasty apple
> tasty banana
> tasty cherry
```


#
## Pass statement

for loops cannot be empty, thus we put in a "pass" if the for loop has no content, to prevent an error.

``` python 
for x in [0, 1, 2]:
    pass
```

