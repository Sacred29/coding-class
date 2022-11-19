# Lesson 4 - Lists, Arrays and Tuples
## Preface
>Lesson and examples are stated in the "python" language. However, lesson objectives can be applied to othe languages with differing syntax.
&nbsp;
&nbsp;

Lists, Arrays and Tuples are known as collections. 

> ### Lesson objectives
> Learn & Apply
>> 1. Difference between lists, arrays and tuples
>> 2. Indexes
>> 3. CRUD lists and arrays
>> 4. iterate through them (via loops.)
>
> #



## Lists
Lists is an ordered collection of data types. 

1. Lists are mutable
2. Lists are dynamic and can contain objects of different data types
3. List elements can be accessed by index number

``` python
x = ["mango", "strawberry", "orange",
        "apple", "banana"]
```

## Arrays
An array is a collection of items stored at contiguous memory locations. The idea is to store multiple items of the same type together, enabling easier calculations of positions by offseting the base value.

An Array is an ordered collection of similar data types.
1. An array is mutable
2. Its elements can be accessed using its index number.
``` python
import array as arr

# creating an array with integer type
a = arr.array('i', [1, 2, 3])

# creating an array with double type
b = arr.array('d', [2.5, 3.2, 3.3])

```


## Tuples
A tuple is an unordered collection and an immutable collection. 
This means that the values within the tuple cannot be changed or replaced.


``` python 
# Tuples are defined by ()
a = ('10', 10, True)
```



## Accessing collection elements via index.

``` python 
a = [1,2,3,4,5]

# elements are accessed via []
# collection indexes start with 0

print(a[0]) # output: 1
print(a[1]) # output: 2
```

## Slice collection elements via index
``` python 
a = [1,2,3,4,5]

# elements are accessed via []
# collection indexes start with 0


# When slicing, it will include the index of beginning index value, however, does not include ending index value (remember that indexes start at 0.)
print(a[0:4]) # output: [1,2,3,4]
print(a[0:5]) # output: [1,2,3,4,5]

# if ending index surpasses length of list, no error will be thrown. All applicable and existing elements will be included.

print(a[0:6]) # output: [1,2,3,4,5]
```