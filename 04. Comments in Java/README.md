# Comments in Java

In Java, comments are used to add explanations or annotations to your code, making it easier to understand. They are ignored by the compiler, so they don’t affect the execution of your program. Java supports three types of comments:

1. **Single-Line Comments**: Single-line comments are used to comment out a single line of code. They begin with `//`.

```bash
// This is a single-line comment
int x = 10; // This is also a single-line comment
```

2. **Multi-Line Comments**: Multi-line comments can span multiple lines and are enclosed between `/*` and `*/`. They are useful for commenting out larger blocks of code or providing detailed explanations.

```bash
/*
 * This is a multi-line comment.
 * It spans multiple lines.
 */
int y = 20;
```
3. **Documentation Comments**: Documentation comments are used to generate API documentation. They are enclosed between `/**` and `*/` and are used to describe classes, methods, and fields. These comments can be processed by tools like Javadoc to produce HTML documentation.

```bash
/**
 * This class represents a simple example.
 * It demonstrates the use of documentation comments.
 */
public class Example {
    /**
     * This method prints a greeting message.
     * 
     * @param name the name of the person to greet
     */
    public void greet(String name) {
        System.out.println("Hello, " + name + "!");
    }
}
```
