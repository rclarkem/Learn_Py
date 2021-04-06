# Strings

Texts is surrounded in quotes either double or single.

ex:

```py
course = "Python Programming"
```

```py
course = 'Python Programming'
```

You can use triple quotes if it is multi lines:

```py
course = """

Hey this is a message

That wraps multiple lines!

You should use triple quotes.

"""
```

<br>

## String Methods

`len` : gives you the length of the string.

```py
course = 'Python Programming'
print(len(course))
# 18
```

Strings are zero indexed; You count the first character at 0.

Can be accessed using bracket notation

ex:

```py
course = 'Python Programming'
print(course[0])
# P
```

Can use negative indexes like `-1`

```py
course = 'Python Programming'
print(course[-1])
# g
```

We can `slice` strings in order to abstract out what we want:

- we need the `[first_index : end_index]` (end index non-inclusive)

```py
course = 'Python Programming'
print(course[0:3])
# Pyt
```
