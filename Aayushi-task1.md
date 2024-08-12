  

# casefold
* convert string into lower case


```python
text = "PYTHON"
```


```python
text.casefold()
print(text.casefold())
```

    python
    

# capitalize
* convert the first character to upper case


```python
text = "iNDIA"
text.capitalize()
print(text.capitalize())
```

    India
    

# endswith
* returns true if the string ends with the specific value


```python
text = " Welcome to my world."
result = text.endswith("world.") 
print(result)
```

    True
    

# FIND
* SEARCHES the strings for a specific value and freturns the position of where it was found


```python
text = "Welcome to my world."
index = text.find("welcome")  
print(index)
```

    -1
    

# upper
* Converts all characters to uppercase.


```python
text = "Hello"
uppercase_string = text.upper()
print(uppercase_string)
```

    HELLO
    

 # lower
* Converts all characters to lowercase.


```python
text = "HELLO"
lowercase_string = text.upper()
print(lowercase_string)
```

    HELLO
    

# startswith
* Returns True if the string starts with the specified prefix.


```python
text = "Hello, welcome to my world."
result = text.startswith("Hello")  # Returns True
print(result)
```

    True
    


```python
text = "Hello, welcome to my world."
result = text.startswith("welcome")  # Returns True
print(result)
```

    False
    

# endswith 
* Returns True if the string ends with the specified suffix.


```python
text = "Hello, welcome to my world."
result = text.endswith("world.")  # Returns True
print(result)
```

    True
    


```python
text = "Hello, welcome to my world."
result = text.endswith("hello.")  # Returns True
print(result)
```

    False
    

# join
* Converts elements of an iterable into a string.


```python
myList = ["a", "b", "c"]
separator = ", "
result = separator.join(myList)
print(result) 
```

    a, b, c
    

# partition
* splits a string into three parts based on the first occurrence of a specified separator


```python
txt = "I could eat bananas all day"
x = txt.partition("bananas")
print(x)
```

    ('I could eat ', 'bananas', ' all day')
    

# isnumeric
* all characters in a string are numeric digits (0-9).



```python
txt = "565543"
x = txt.isnumeric()
print(x)
```

    True
    


```python
txt = "565fgh3"
x = txt.isnumeric()
print(x)
```

    False
    


```python

```
