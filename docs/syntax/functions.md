Functions are important building blocks in programming languages that allow code reuse and aid in the organization of code.
They allow us to group code into logical units that can be called from other parts of our program.
On this page, we will compare function declaration and invocation in some popular programming languages.

## Function Declaration

In both Kotlin and Python, functions must be declared before they can be used.
However, the syntax for declaring functions is slightly different in each language.

### Kotlin

#### Signature

In Kotlin, functions are declared using the `fun` keyword, followed by the function name, parameter list, and return type (if any[^1]).
The following function accepts a parameter `name` of type `String`. It does not return a value.

[^1]: Here, "if any" refers to any return type other than `Unit`, the singleton used when no return value exists.
`Unit` is analogous to `void` in Java.
Please note all methods in Kotlin must return a value, and that the appropriate return type and statement are automatically inserted by the compiler.

```kotlin
fun broadcast(name: String) {
    println("Hello from $name!")
}
```

A function with a return type is declared as follows:

```kotlin
fun greet(name: String): String {
    return "Hello, $name!"
}
```

