# Python Loops

There are some times when you need to perform the same operation repeatedly in Python, and in that case, Python loops come in handy. Say, you want to print the table of a number reciaved from the user. So now lets see what can we do without using loops.
```python
number = input('Enter a number: ')
print(number * 1)
print(number * 2)
print(number * 3)
print(number * 4)
print(number * 5)
print(number * 6)
print(number * 7)
print(number * 8)
print(number * 9)
print(number * 10)
```
```
Enter a number: 5
5
10
15
20
25
30
35
40
45
50
```
[Try it out](https://onlinegdb.com/e4tBEcUZQ)

This method is time consuming, and not good for larger projects. So, over here, if we use while loop, then it would be better. While loop is one of the two python loop types. So, this code can explain you how to use while loop.
```python
number = input('Enter a number: ')
count = 1
while count <= number:
    print(count * number)
    count = count + 1
```
```
Enter a number: 5
5
10
15
20
25
30
35
40
45
50
```
[Try it out](https://onlinegdb.com/XT-ZEsOkp)

So this is about while loops. For loops are not going to be explined in this tutorial, but you can learn it from [this video](https://youtu.be/A_WIv0XA67k)

[Previous](user_input.md)
[Next](conditions.md)