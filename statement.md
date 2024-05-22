# PYTHON: The "index()" Function.
In this playground, we are going to take a look at Python's built-in ```index()``` function.

Before we do that, I want to make clear that the ```index()``` function can be used for Strings, Lists and Tuples.
We will look at how the function is used for each of those.

I'd also like to make clear that the ```index()``` function works for 0-based indexes.
```python
# A "0-based index" is an index that begins at 0.

txt = "abcde"
# In txt "a" is indexed 0, "b" is indexed 1, "c" is indexed 2, etc.
```

Now, let's begin.

## Program 1: Using ```index()``` on Strings
We can use the ```index()``` function to find the position (or index) of the first character of a substring in a string:
```python runnable

string = "Hello World!"

print(string.index("World!")) # The first letter of this substring in at index 6.
```
