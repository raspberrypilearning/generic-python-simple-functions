## Creating Simple Functions in Python

Sometimes you will want to use the same few lines of code, multiple times within your script. Alternatively, you want to have the same few lines of code run, every time a certain event occurs; maybe when a user presses a certain key, or types a specific bit of text. Either way, it's at such times that you might want to consider using a **function**

Functions are **named** blocks of code that perform a specific task. Just about the simplest function you could create in Python would look like this:

```python
def hello():
    print('Hello World!')
```

You tell Python that you're creating a new function by using the `def` keyword, followed by the name of the function. In this case it was called `hello`. The parenthesis after the function name are important, and if you want to know more about why they are included, then have a look at [this resource on using parameters](LINK TO RESOURCE).

The colon at the end of that line indicates that the code that is inside the function will be indented below the line, just like in a `for` or `while` loop or an `if`/`elif`/`else` conditional.

You can **call** a function by typing it's name with the parenthesis included. So to run this function you would type `hello()`. Here's the complete program.

*[call]: run the lines of code within the function

```python
def hello():
    print('Hello World!')

hello()
```

You can have multiple lines of code inside a function if you like, but you should be careful about using variables. Any variable inside a function is said to be **local** to that function. That is, the any code outside of the function won't have access to variable inside the function. For instance here is a simple function:

```python
def say_hello():
    word = "Hello"
	print(word)
```

The variable `word` is local to the function. We say that the variable is in the functions' **scope**. That means you can't use that variable outside of the function. For instance, this code would error.

```python
def say_hello():
    word = "Hello"
	print(word)

print(word)
```

This errors because the variable `word` is outside of the scope of the main program. Here's another example:

```python
word = "Goodbye"

def say_hello():
    word = "Hello"
	print(word)

print(word)
```

Here, the word `Goodbye` will be printed, as the variable `word` is now also a **Global** variable that is in the scope of the main program.


