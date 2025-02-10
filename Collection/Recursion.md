Recursion is the process of a[[Javascript Functions | function]] calling itself.

```python
def call_for_lunch(person):
2    if person == 'Carly': # BASE CASE
3        return True
4    return call_for_lunch(next_person) # RECURSIVE CALL
```

1. Base case/exit, e.g. Carly doesn't call anyone else, she just says yes and hangs up.
2. Recursive call, ie calling the function itself with different argument

Here's a classic textbook example: finding the factorial of a number (5! = 5*4*3*2*1)

```python
1def factorial(n):
2    if n <= 1: # BASE CASE
3        return 1
4    return n * factorial(n - 1) # RECURSIVE CALL
```

How does the computer accomplish such a feat as calling a function itself? 

It uses a stack behind the scene to keep track of where things are 
```python

def factorial_stack(n):
2    stack = []
3    # push each call to a stack
4    # top of the stack is base case
5    while n > 0:
6        stack.append(n)
7        n -= 1
8
9    res = 1
10    # pop and use return value until stack is empty
11    while stack:
12        res *= stack.pop()
13
14    return res
```

A computer internal stack is called call stack and the data it pushes onto a call stack are called stack frames. Stack Frames on a call stack represent the function you are calling and its arguments.



#SWE