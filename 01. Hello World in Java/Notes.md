# Introduction
Let us output a number in Java.

Java has a few lines of code which we write in almost all programs.
These are the first 3 lines that you see in the program to your right. We are going to learn about all of them in some time.

For now, read the Line 6:
System.out.println(12);

This is what we use to output/print anything to the screen. Note that this line contains a (;) semicolon at the end. Semicolon is mandatory at the end of statements in Java.

This code just prints 12 on the screen when you run it.

## Printing text
In the last problem, we saw how to print a number (using System.out.println).

Let's see how to output some text.

There is only one difference with printing a number: all textual content should start and end with double quotes ("").

For example, we output a number like this
```bash
System.out.println(10);
```

But to output a text, we do this
```bash
System.out.println("I love Java");
```

# Comments
In last section, you might have noticed this symbol // and some text instruction in the code editor. That was a **comment**.

Comments in Java are notes added to code to explain what the code does or any other kind of information about the code. They are helpful for making the code easier to understand.

## Types of Comments in Java
In Java, there are two primary ways to add comments to your code:

### Single-Line Comments:

- Syntax: // Your comment here
- Example:
```bash
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); // This is a single-line comment. It prints "Hello, World!".
    }
}
```
Single-line comments start with // and continue to the end of the line. They are useful for adding brief explanations or notes about specific lines of code.

### Multi-Line Comments:

- Syntax: /* Your multi-line comment here */
- Example:
```bash
/* 
  This is a multi-line comment
  spanning multiple lines
*/
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
Multi-line comments start with /* and end with */. They can span multiple lines and are typically used for longer explanations or for commenting out large blocks of code.

## Best Practices for Using Comments in Java
- Be Descriptive: Always strive to write clear and descriptive comments that explain the purpose, functionality, or reasoning behind the code.

- Update Regularly: Remember to update comments when you modify the code to ensure they remain accurate and relevant.

- Avoid Redundancy: Avoid writing comments that only restate the obvious. Comments should provide additional information or insights that are not immediately evident from the code itself.

***

# Review and Reflect - Print
In this lesson, we learned about how to output numbers and text in Java using print statement.

To print numbers, we just add them inside print:
```bash
System.out.println(20);

// Output:
// 20
```
Don't forget the semicolon (;) at the end of line.

Also, we can do mathematical operations inside print statement itself, like addition, subtraction etc.
```bash
System.out.println(2 + 2);
System.out.println(1 - 2);

// Output:
// 4
// -1
```
To print text, we use double quotes:
```bash
System.out.println("I am learning Java");

// Output:
// I am learning Java
```
You get an error if you don't add double quotes when printing text. Also, any text that start with // is called a comment and Java ignores these lines when running your code.

In the next lesson, we will learn about how we can use print statement to print on multiple lines or multiple texts on same line, and do more complex mathematical operations.
