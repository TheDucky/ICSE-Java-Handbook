# 5. Input Output in Java (IO)

Input is used to retrieve data from the user. This system provides user-friendly environment to input the data values in Java programming. The `Scanner` class will the used to retrieve data from the user. The `Scanner` class is located in the `java.util` package (java.util.Scanner). To use this class, you must import it by using the import keyword.

### Getting Data from Scanner class

**_To import the class_**
```java
import java.util.Scanner; // This will only import the Scanner class
import java.util.*; // This will import all packages located in util
```

**_To create and close Scanner class_**
```java
// Create
Scanner scan = new Scanner(System.in);
// object objectName = new ...

//Close
scan.close();
// objectName.close()
// We close the scanner to prevent any data leaks while the program is running.
```

----

Data Type | Method | Returns | Error (if any)
:--------:|:------:|:-------:|:------------:|
`int`    | `.nextInt()`    | Returns the next token as an int | If the next token is not an integer, InputMismatchException is thrown
`long`   | `.nextLong()`   | Returns the next token as a long | If the next token is not an integer, InputMismatchException is thrown
`float`  | `.nextFloat()`  | Returns the next token as a float| If the next token is not a float or is out of range, InputMismatchException is thrown
`double` | `.nextDouble()` | Returns the next token as a double| If the next token is not a float or is out of range, InputMismatchException is thrown
`String` | `.next()`       | returns the next complete token from this scanner and returns it as a string; a token is usually ended by whitespace | If not token exists, NoSuchElementException is thrown
`String` | `.nextLine()`   | Returns the rest of the current line excluding any line separator at the end | " "

----

### Types of Errors
1. Syntax errors
2. Runtime errors
3. Logic errors

----

**_Syntax errors:_**

In effect, syntax errors represent grammar errors in the use of the programming language.
Common examples are:

- Misspelled variable and function names
- Missing semicolons
- Improperly matches parentheses, square brackets, and curly braces
- Incorrect format in selection and loop statements

----

**_Runtime errors:_**

They occur when a program with no syntax errors asks the computer to do something
that the computer is unable to reliably do. Common examples are:

- Trying to divide by a variable that contains a value of zero
- Trying to open a file that doesn't exist

----

**_Logic errors:_**

They occur when there is a design flaw in your program. Common examples are:

- Multiplying when you should be dividing
- Adding when you should be subtracting
- Opening and using data from the wrong file
- Displaying the wrong message

----

### Comments in Java

```java
// This is a single line comment

/*
This is
a multi line
comment
*/

/**
This is
a documentation
comment
*/
```

----

### Output using System class

```java
System.out.print("Java") // the cursor remains in the same line after producing the result
System.out.println("Coffee") // take the cursor to the next line of the terminal window after producing
System.out.prinltf("Joe"); // printf stands for print format
// Inherited from the language C. It gives way more power and functionality to output the desiered content. It is not in syllabus but if you are interested to learn more about it watch https://youtu.be/c2B_Av3x65s
```

----