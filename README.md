# Jio_learning

# java

```java

public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

- In Java, every application begins with a class name, and that  class must match the filename .

- Every line of code that runs in Java must be inside a class.  A class should always start with an uppercase first letter

- The main() method is required
- Any code inside the main() method will be executed. 

- every Java program has a class name which must match the filename, and that every program must contain the main() method.

- Inside the main() method, we can use the println() method to print a line of text to the screen

```java 

public static void main(String[] args) {
  System.out.println("Hello World");
}

```
Note: The curly braces {} marks the beginning and the end of a block of code.

System is a built-in Java class that contains useful members, such as out, which is short for "output". The println() method, short for "print line", is used to print a value to the screen (or a file).

## The Print() Method
There is also a print() method, which is similar to println().

The only difference is that it does not insert a new line at the end of the output

## Java Variables
Variables are containers for storing data values.

In Java, there are different types of variables, for example:

String - stores text, such as "Hello". String values are surrounded by double quotes
int - stores integers (whole numbers), without decimals, such as 123 or -123
float - stores floating point numbers, with decimals, such as 19.99 or -19.99
char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
boolean - stores values with two states: true or false

### Final Variables
If you don't want others (or yourself) to overwrite existing values, use the final keyword (this will declare the variable as "final" or "constant", which means unchangeable and read-only):

```java 
final int myNum = 15;
myNum = 20;  // will generate an error: cannot assign a value to a final variable
```