# 4. Operators in Java

An operator is basically a symbol or token, which performs mathematical operations and gives meaningful results. Some of the types are.

1. Arithmetic Operators
2. Unary Operators
3. Assignment Operator
4. Relational Operators
5. Logical Operators
6. Ternary Operator
7. new Operator
8. Dot Operator

----

**_Unary operators_** needs only one operand. **_Assignment operator_** is used to assign a value to any variable. The **_'new' operator_** in java is responsible for the creation of new object. The **_dot (.) operator_** is also known as member operator it is used to access the member of a package or a class. 

----

### Increment operator,

used for incrementing the value by 1.

- **_Post-Increment:_** Value is first used for computing the result and then incremented.
- **_Pre-Increment:_** Value is incremented first and then result is computed.

```java
//Post-Increment
int i = 1;
System.out.println(i++); // OUTPUT: 1
System.out.println(i++); // OUTPUT: 2
```

```java
//Pre-Increment
int i = 1;
System.out.println(++i); // OUTPUT: 2
System.out.println(++i); // OUTPUT: 3
```

----

### Decrement operator,

used for decrementing the value by 1.

- **_Post-Decrement:_** Value is first used for computing the result and then decremented.
- **_Pre-Decrement:_** Value is decremented first and then result is computed.

```java
//Post-Decrement
int i = 3;
System.out.println(i--); // OUTPUT: 3
System.out.println(i--); // OUTPUT: 2
```

```java
//Pre-Decrement
int i = 3;
System.out.println(--i); // OUTPUT: 2
System.out.println(--i); // OUTPUT: 1
```

----

### Arithmetic Operators: 

They are used to perform simple arithmetic operations on primitive data types.

- `*` Multiplication
- `/` Division
- `%` Modulo
- `+` Addition
- `–` Subtraction

----

### Relational and Logical Operators: 

**_Relational operators_** are used to check for relations like equality, greater than, less than.

- `==` Equal to
- `!=` Not equal to
- `<` Less than
- `>` Greater than
- `<=` Less than or equal to
- `>=` Greater than or equal to

**_Logical operators_** are used to perform "logical AND" and "logical OR" operation.

- `&&` Logical AND
- `||` Logical OR

**_Note:_** The best way to understand this concept and write a program is by swaping the operator symbol with its meaning in readable language. Like so:~
```java 
if(1 == 1 && 1 <= 3) {
	return true;
} // If 1 is equal to 1 and 1 is less than or equal to 3


if(2 != 3 || (1+1) = 1) {
	return false;
} // If 2 is not equal to 3 or 1 plus 1 is equal to 1
```

----

### Ternary operator: 
They are a shorthand version of if-else statements. It has three operands and hence the name ternary.

```java
// SYNTAX

// Normal if:
if(Expression1)
{
    variable = Expression2;
}
else
{
    variable = Expression3;
}

//-----------------------------//

// Ternary operator:
variable = Expression1 ? Expression2: Expression3
```

**_Example_**

```java
int a = 3, b = 4 max;

if(a > b) {
	max = a;
}else {
	max = b;
}

// Or by using the ternary operator
max = (a > b) ? a : b;
```

----