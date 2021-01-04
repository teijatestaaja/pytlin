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

 ## [Lesson 3: Variables](#lesson3)

In Python, a variable is a symbolic name that is a reference or pointer to an object. In other words, a variable is a reserved memory location to store value. There is no need to declare variable's type, but variables need to be assigned a value or 'None'. Any variable may also be assigned a value of one type and then later re-assigned a value of a different type:

 ```python
 >>> x = 5
 >>> x = "five"
 >>> y = None
 ```

In Kotlin variables are introduced using either val or var. Variables that are defined using keyword val are immutable, whereas variables defined with var are mutable and can be re-assigned a value. Kotlin is statically typed programming language, which means that variables need to be defined before they are used. The type of the variable is usually inferred. You can give the type of the variable, but it is nesessary only when the variable's value is not given immediately.

```kotlin
 val x = 5
 var y: String
 var z = 5.0
 y = "five"
 ```

