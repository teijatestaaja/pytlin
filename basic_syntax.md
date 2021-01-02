# Basic syntax

## [Lesson 1: Printing](#lesson1)

The print() function prints the given object to the standard output screen or to the text stream file.

Python: [print](https://docs.python.org/3/library/functions.html#print)

```python
>>> print("Python is a cool programming language!")
```

In Python you can print more than one object, and you can specify the separator:

```python
>>> print("Hello", "world", sep="\n")
```

Kotlin: [print](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.io/print.html)

```kotlin
print("Kotlin is a cool programming language!")
```

## [Lesson 2: Creating strings](#lesson2)

 In both Python and Kotlin, creating strings is as simple as assigning a value to a variable. Also in both Python and Kotlin, the strings are immutable. This means that you cannot change individual character of a string. However, you can reassign a string variable again in Python and also in Kotlin if you declared the variable using keyword "var". Reassigning a string creates a new string in both languages.
 
 Python treats single quotes the same as double quotes. You can access elements of a string by using indexing, ie. square brackets:

 ```python
 >>> word1 = "Hello"
 >>> word2 = 'Hello world'
 >>> print(word1[0])
 ```

 In Kotlin, all strings are objects of String class. In Kotlin a string can be declared with double quotes but not with single quotes. Similarly to Python, in Kotlin elements of a string are characters that can be accessed by the indexing operation:
 
 ```kotlin
 var word1 = "Hello"
 var word2 = "Hello world"
 print(word1[0])
 ```