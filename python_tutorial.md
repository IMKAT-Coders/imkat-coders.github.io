# Python Tutorial
## By Ishan Kuber
---

![Python](https://assets.stickpng.com/images/5848152fcef1014c0b5e4967.png)

# Introduction to Python

What is Python?

Python is a very popular programming language. This language is easy to learn, and yet, we can build cool applications with it with lots of cool features. And that is why it is my favourite programming language too!

So are you excited to learn Python? 
Lets get started

# Basic Python Syntax

Ok, so now after a brief introduction to Python, lets move towards the actual coding part.

Download Python with the help of [this video](https://youtu.be/kV69k0kK6BM) from [python.org](python.org). Also, dowload PyCharm, which is a very popular IDE for python from [jetbrains.com](https://www.jetbrains.com/pycharm/download/). Be sure to download the community edition which is free of cost.

See the code below, which will output 'Hello World'.  
Every time when you see a code like this, the output will be given in the box below.
```python
print('Hello World')
```
```
Hello World
```
Now, did you see how easy it is? And that is the main reason Python is so popular.

Now, just note that this Python tutorial will not be able to make you understand everything clearly, but can obviously provide you the things like the important links and all.  
Also, you can grab the code from here for editing. But if you really want all the proper explanations, then see my [Python Course on Youtube](https://youtube.com/playlist?list=PLmWXQgLAMBwHvlK34hUbFjiQ4CztrRoL8).

So now let us move on to Python Variables

# Python Variables

Python Variables are type of boxes in real life, which store something. So now lets take a look at this simple code containing variables.
```python
text = "Hello World"
print(text)
```
```
Hello World
```
You see, we made a so called box in which we stored the text 'Hello World' and labeled that box as 'text'.

Now note that while prinitng that variable called text (referred as box), I didn't use quotation marks. Because if I do, then the variable name 'text' will be printed on the screen. Now this is just the basic part of variables. We will learn more about them in the next section, in which we will study data types.

# Data Types in Python
Don't worry about what are data types. Lets just see which data types do we have.

There are 4 Data Types in Python
1. String
2. Integer
3. Float
4. Boolean

Now let us see each data type in detail

# String

String is a sequence of characters. So, to simplify this, we can say that a string is basically some group of letters, numbers and signs, just like sentences. But the only thing that differentiates strings from normal sentences is that a string must be in quotation marks where as sentences shall not necessarily be. So lets take an example of our first 'Hello World' code.
```python
print('Hello World')
```
```
Hello World
```
So in this simple example, 'Hello World' is a string. Lets take another example with variables and strings.
```python
text = 'Hello World'
print(text)
```
```
Hello World
```
This is also an example which we saw earlier in the varables section. So over hee too, 'Hello World' is a string. We will talk about strings in the later part of this tutorial. So lets stop with it now

# Integer

Now, Integers, as you know, are integers in maths. So no need to explain it. But still for convenience,  I will show you a sample code.
```python
integer = 13
print(integer)
```
```
13
```
Now see that integers are not stored in quotation marks. And to print integers without using variables, use this type of code.
```python
print(13)
```
```
13
```
So thats all about integers for now.

# Float

Float is a data type which can hold values wit floating point numbers. To simplify this, float is a data type which can have a number with a decimal point. So it is very easy and also doesn't need much explanation. So we will just see a code example and stop.
```python
number = 12.345
print(number)
```
```
12.345
```
This is an example with variables. But variables take up memory, so we can even directly print the value like this.
```python
print(12.345)
```
```
12.345
```
So that's it for floats now.

# Boolean

Now boolean is a really different data type which can store only 2 values: True and False.

Now these True and False values should start with capital letters and not small, becuase python is case sensetive.  
Also, these values shall not be in quotation marks.

So lets take a look at a few examples.
```python
is_online = True
print(is_online)
```
```
True
```
Without variables, it will be like.
```python
print(True)
```
```
True
```
Or, with False.
```python
is_online = False
print(is_online)
```
```
False
```
Ok, so thats it for booleans now. And this ends our Data Types section. Now next, we are going to cover a very interesting topic.

# User Input