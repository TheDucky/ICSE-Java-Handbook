# 3. Values and Data Types

### Data type

Data type specifies the size and type of values that can be stored in an identifier. They can be classified into two types:

- **_Primitive_** (Integer, Character, Boolean, Float)
- **_Non-Primitive_** (Classes, Interfaces, Arrays)

Data Type | Size | Default Value | Example 
:--------:|:----:|:-------------:|:------:
`byte`    |1 byte |0        |123
`short`   |2 bytes|0        |32766
`int`     |4 bytes|0        |2,147,483,645
`long`    |8 bytes|0        |9,223,372,036,854,755,806
`float`   |4 bytes|0.0f     |3.2f
`double`  |8 bytes|0.0d     |8.583
`char`    |2 bytes|'\u0000' |'D'
`boolean` |1 byte |false    |true & false
`String`  |-      |null     |"Hello World"

----

### Java Tokens
A token is the smallest element in a program that is meaningful to the compiler. These tokens define the structure of the language.

1. **_Identifiers_** are names provided by you. These can be assigned to variables, methods, functions, classes etc. to uniquely identify them to the compiler.

2. **_Keywords_** are reserved words that have a specific meaning for the compiler. They cannot be used_** as identifiers. Java has a rich set of keywords.

3. **_Literals_** are variables whose values remain constant throughout the program. They are also called Constants

4. **_Operators_** are a symbol that operates on one or more operands to produce a result. They will be discussed in greater detail in the next article.

5. **_Separators_** are symbols that indicate the division and arrangement of groups of code. The structure and function of code is generally defined by the separators.

	- **_parentheses ( )_** Used to define precedence in expressions, to enclose parameters in method definitions, and enclosing cast types.
	- **_brackets [ ]_** Used to declare array types.
	- **_braces { }_** Used to define a block of code and to hold the values of arrays.
	- **_semicolon ;_** Used to separate statements.
	- **_comma ,_**
	- **_period ._**

----

### Variables

1. **_Instance Variables (Non-Static Fields) :_** Objects store their individual states in “non-static fields”, that is, fields declared without the static keyword.

2. **_Class Variables (Static Fields) :_** A class variable is any field declared with the static modifier; this tells the compiler that there is exactly one copy of this variable in existence; regardless of how many times the class has been instantiated.

3. **_Local Variables :_** A method stores its temporary state in local variables. The syntax for declaring a local variable is similar to declaring a field (for example, int count = 0;).

4. **_Parameters :_** They are the variables that are passed to the methods of a class.

----

### Initialisation

- **_Static Initialization_** – uses direct assignment of a constant to a defined variable

```java
int i = 201; // Here the value of 'i' is assigned before runtime
System.out.println(i);
```

- **_Dynamic Initialization_** – a variable will get initialized at run time.

```java
Scanner scan = new Scanner(System.in);
int i = scan.nextInt(); // Here the value of 'i' is assigned during runtime by the user
System.out.println(i);
```

----

### Arrays

An array is a group of variables that share the same data type, and are referred to by a common name. Arrays of any type can be created and may have one or more dimensions.

```java
int arrayExample[] = {1, 2, 3, 4};
```

----

### Escape sequences

There are some non-graphic characters, which are used to direct the cursor while printing. These characters are frequently used in java programming called as escape sequences.

Escape Sequence | Description
:--------------:|:----------:
`\t` |Insert a tab in the text at this point.
`\b` |Insert a backspace in the text at this point.
`\n` |Insert a newline in the text at this point.
`\r` |Insert a carriage return in the text at this point.
`\f` |Insert a form feed in the text at this point.
`\'` |Insert a single quote character in the text at this point.
`\"` |Insert a double quote character in the text at this point.
`\\` |Insert a backslash character in the text at this point.

----

### Conversion of Data Types

**_Implicit Conversion_** Also known as **_widening conversion_**. Converting from smaller data type like `int` to larger data type like `long`.

```java
// Syntax for Implicit Conversion
int a = 10;
byte b = a;
```
**_Implicit Conversion_** Also known as **_narrowing conversion_**. Converting from larger data type like `long` to smaller data type like `int`.

```java
// Syntax for Explicit Conversion
long b = 21;
int a = (int)b;
```

**_Note:_** An error to look out for `error: incompatible types: possible lossy conversion`. This is because the conversion from one data type to another was not done properly (Wrong syntax was used).

----

### Final Keyword

The final keyword is a non-access modifier used for classes, attributes and methods, which makes them non-changeable (impossible to [inherit](../Dictionary.md#inherit) or [override](../Dictionary.md#override)).

**_Example_**

```java
final float pi = 3.14f;

// Note: if value with the final keyword like 'pi' was to be changed it will throw an error. 
pi = 41.3f
// error: cannot assign a value to final variable
```

----