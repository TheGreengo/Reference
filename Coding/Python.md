# Python Coding Reference Guide

## Hello World
```python
print("Hello World!")
```

## Conditionals
"If", "else-if", and "else" statements take the following form:
```python
if var1 < var2:
  somethingHappens()
elif var2 < 3:
  somethingElseHappens()
else:
  lastlyThisHappens()
```

## Functions
The function syntax is quite simple
```python
def myFunc(parameters):
  result = parameters
  return result
```

## Arrays

## Classes
The syntax for defining the a class in python is:
```python
class myName:
  property = 4
```
To define constructors and to string functions are defined as ```__init__``` and ```__str__``` respectively, with "self" being one of the 
parameters passed in (you don't have to use the name ```self```):
```python
class myName:
  def __init__(self,property):
    self.property = property
  def __str__(self):
    return f"Property: {self.property}"
```
Note: the ```str``` function above uses an fstring which is a formatable string where we can insert variable values.

