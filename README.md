# Q4-project
Learning introductory Python course:
https://www.codecademy.com/enrolled/courses/learn-python



# Python Syntax
- `Print` --> like document.write()
- Make single or multi-line comments using # or """

COMMON METHODS:
- `len()`
- `.upper()` --> like .toUpperCase()
- `.lower()` --> like .toLowerCase()
- `str()`
- `.sort()`
- `.insert()`
- `max()`
- `min()`
- `abs()`
- `type()`

DATA/INPUT TYPES:
- `int` integers (3, 0, -5)
- `float` decimals (-0.5, 3.14)
- `str` sequences of characters ("hi", "what's up?")
- `list`
- `dict`
- `boolean`
- Convert between data types using int(), float(), str()
<p><br></p>

# Functions
SETUP:
```Python
def functionName():
  # body code is always indented!
```

FOR LOOPS:
- Works for strings, lists, dictionaries
```Python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print fruit
# prints apple, banana, cherry
```

IF/ELSE STATEMENTS:
- use "elif" = else if
```Python
age = 25

if age < 13:
    print "Child"
elif age >= 13 and age < 20:
    print "Teenager"
elif age >= 20 and age < 65:
    print "Adult"
else:
    print "Senior"

# prints "Adult"
```

# Lists
REMOVING ELEMENTS:
- `.pop(index)`
- `.remove(item)`
- `del(x[1])`
