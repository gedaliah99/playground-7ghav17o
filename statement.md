# PYTHON: The Index() Function.
In this playground, we are going to take a look at Python's built-in ```index()``` function.

Before we do that, I want to make clear that the ```index()``` function can be used for Strings, Lists and Tuples.
We will look at how the function is used for each of those.

I'd also like to make clear that the ```index()``` function works for 0-based indexes.
```python
# A "0-based index" is an index that begins at 0.

string = "abcde"
# "a" is indexed 0, "b" is indexed 1, "c" is indexed 2, etc.

list = ["a", "b", "c", "d", "e"]
# "a" is indexed 0, "b" is indexed 1, "c" is indexed 2, etc.
```

Now, let's begin.

## Program 1: Using ```index()``` on Strings
We can use the ```index()``` function to find the position (or index) of the first character of a substring in a string:

```python
# Syntax:
string.index(substring, start, end)
```

Here's an example of the function in action:

```python runnable
string = "Hello World!"

print(string.index("World!")) # The first letter of this substring in at index 6.
```

We can also use it to find the position (or index) of first occurence of a character in a string:
```python runnable
string = "Hello World!"

print(string.index("l")) # There are three letter l's in "Hello World!", but the first occurence is at index 2.
```
::: Did You Know?
The ```index()``` function does almost exactly the same thing as Python's ```find()``` function.

This is true, but there is one slight difference.

```index()``` will raise an error, while ```find()``` will return ```-1```.

```python runnable
string = "Hello World!"

print(string.find("a"))  # Will return -1, because "a" is not in the string.
print(string.index("a")) # Will raise an error, because "a" is not is the string.
```
:::

## Program 2: Using ```index()``` on Lists
We can also use the ```index()``` function to find the position (or index) of an element in a list.
```python
# Syntax:
list.index(element)
```

Here's an example of the function in action:
```python runnable
list = ['H', 'e', 'l', 'l', 'o']

print(list.index("e")) # The only occurence of "e" is at index 1.
```

## Program 3: Using ```index()``` on Tuples
We can also use the ```index()``` function to find the position (or index) of a value in a tuple.
```python
# Syntax:
tuple.index(value)
```

Here's an example of the function in action:
```python runnable
tuple = (1, 3, 7, 8, 7, 5, 4, 6, 8, 5)

print(tuple.index(8)) # The first occurence of "8" is at index 3.
```


### Conclusion:
In this playground we:
 - Took a look at Python's ```index()``` function.
 - Saw it in action working with Strings, Lists, and Tuples.
 - Compared it to Python's ```find()``` function.

Please feel free to use this code and implement it in CoC's or programs you make.

Thanks for reading, I hope this playground has been helpful.

#### Links and Further Information
Here is a "list" of links that you can visit to get further information on the ```index``` function and the ```find``` function:
1. https://www.w3schools.com/python/ref_string_index.asp
2. https://www.w3schools.com/python/ref_list_index.asp#gsc.tab=0
3. https://www.w3schools.com/python/ref_tuple_index.asp