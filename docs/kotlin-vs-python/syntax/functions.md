Functions are important building blocks in programming languages that allow code reuse and aid in the organization of code.
They allow us to group code into logical units that can be called from other parts of our program.
On this page, we will compare function declaration and invocation in two popular programming languages, Kotlin and Python.

## Function Declaration

In both Kotlin and Python, functions must be declared before they can be used.
However, the syntax for declaring functions is slightly different in each language.

### Kotlin

In Kotlin, functions are declared using the `fun` keyword, followed by the function name, parameter list, and return type (if any*).

```kotlin
fun greet(name: String): String {
    return "Hello, $name!"
}
```

