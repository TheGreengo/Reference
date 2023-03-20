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
elif var2 < var 3:
  somethingElseHappens()
else:
  lastlyThisHappens()
```

## Functions

## Arrays

## Classes
The syntax for defining the a class in python is:
```python
class myName:
  property = 4
```
To define constructors and to string functions are defined as ```__init__``` and ```__str__``` respectively, with "self" being one of the 
parameters passed in (```self``` can also be defined as a different name as well):
```python
call myName:
  def __init__(self,property):
    self.property = property
  def __str__(self):
    return f"Property: {self.property}"
```
