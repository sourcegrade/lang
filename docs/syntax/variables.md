Variables are an essential concept in programming languages.
They allow us to store and manipulate values, making it easier to work with data in our code.
On this page, we will compare variable declaration and assignment in two popular programming languages, Kotlin and Python.

## Variable Declaration

In both Kotlin and Python, variables must be declared before they can be used.
However, the syntax for declaring variables is slightly different in each language.

### Kotlin

In Kotlin, variables can be declared using the `val` and `var` keywords, where `val` declared a read-only variable (analog to `final` in Java) and `var` declares a mutable variable.
The syntax for declaring a variable is as follows:

```kotlin
val readOnlyVariable = 5
var readWriteVariable = "Hello World"
```

In the above example, the types of the variables are inferred by the compiler.
However, you can also explicitly specify the type of a variable (semantically equivalent to the previous example):

```kotlin
val readOnlyVariable: Int = 5
var readWriteVariable: String = "Hello World"
```

Once a variable has been declared, it cannot be reassigned to a value of a different type.

### Python

In Python, variables are declared by assigning a value to them.
The syntax for declaring a variable is as follows:

```python
myVariableA = 5
myVariableB = "Hello World"
```

Python is a dynamically typed language, so the type of a variable is inferred by the interpreter.
It also is possible to reassign a variable to a value of a different type:

```python
myVariableA = 5
myVariableA = "Foo"
```
