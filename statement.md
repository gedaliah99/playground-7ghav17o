# PYTHON: The "index()" Function.
In this playground, we are going to take a look at Python's built-in ```index()``` function.

Before we do that, I want to make clear that the ```index()``` function can be used for Strings, Lists and Tuples.
We will look at how the function is used for each of those.

Now, let's begin.

## Program 1: Using ```index()``` on Strings
We can use the ```index()``` function to find the position (or index) of a substring in a string:
```python runnable

string = "This is a string containing a substring."

sub_string = "substring."

print(string.index(sub_string))

```
