Sometimes you will want to use the same few lines of code multiple times within your script. Alternatively, you want to have the same few lines of code run every time a certain event occurs; maybe when a user presses a certain key, or types a specific bit of text. Either way, it's at such times that you might want to consider using a **function**

Functions are **named** blocks of code that perform a specific task. Just about the simplest function you could create in Python would look like this:

```python
def hello():
    print('Hello World!')
```

You tell Python that you're creating a new function by using the `def` keyword, followed by the name of the function. In this case it is called `hello`. The parentheses after the function name are important.

The colon at the end of that line indicates that the code that is inside the function will be indented below the line, just like in a `for` or `while` loop or an `if`/`elif`/`else` conditional.

You can **call** a function by typing its name with the parentheses included. So, to run this function you would type `hello()`. Here's the complete program.

*[call]: run the lines of code within the function

```python
def hello():
    print('Hello World!')

hello()
```


