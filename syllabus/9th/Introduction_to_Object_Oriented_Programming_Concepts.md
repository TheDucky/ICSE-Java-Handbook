# 1. Introduction to Object Oriented Programming Concepts

## UNIT 1: Principles of OOP

### High level language

The high-level language is easier to learn as they closely resemble to human language. It is easy to learn, easy to write and [debug](Dictionary.md#debugging). The high-level language is converted into machine language by one of the two different languages translator programs; [interpreter](Dictionary.md#interpreter) or [compiler](Dictionary.md#compiler).

----

### 2 categories of high level language

- **Procedural-Oriented language (POP)** 
	- Gives stress on the functions rather than data items.
	- It allows free flow of data throughout the program.

- **Object-oriented programming (OOP)**
	- Gives stress on the data items rather than functions.
	- The data is restricted, to be used in a specific program area.
	- It makes the complete program simpler by dividing into number of [objects](Dictionary.md#object).
	- The concept of data hiding enhances security in programs.

----

### Basic Principles of Object Oriented Programming

**Abstraction:** is the act of representing essential features without including the background details. (hiding
unwanted details)

**Inheritance:** is a mechanism by which one object acquires the properties and behaviors of the parent object. It’s essentially creating a parent-child relationship between classes.

**Polymorphism:** is when a single word can have many meanings and functions. One form of polymorphism in Java is _'method overloading'_.

**Encapsulation:** is the system of wrapping data and functions into a single unit. (implements data hiding)

----

## UNIT 2: Introduction to Java

### Introduction

Java is a simple, object oriented, high performance language created at _Sun Microsystems by James Gosling in 1990_. Java is famous for its ability to compile to platform independent byte code. Today it is one of the most popular programming language. It powers large webapps with the spring framework, big data pipelines with hadoop, mobile apps on android and even the NASA Maestro Mars rover. Unlike most other programming languages it is both a comiled and interpreted language. What makes Java different is that it compiles to byle code instead of machine code which can run on any operating system without the need to recompile. _(WORA)_ **W**rite **O**nce **R**un **A**nywhere.

----

### Byte Code

Byte code is a highly optimized set of instructions designed to be executed by the Java runtime system, which is called the Java Virtual Machine (JVM). It is an interpreter for bytecode.

----

### Java Compiler and Interpreter

Java compiler is software that converts source code into intermediate binary code called byte code. JVM accepts byte code and converts it into machine code suitable to the specific platform.

![Java Compilation Process](/Images/JavaCompilationProcess.png)

----

### Java Libraries
Java packages are a collection of various classes. Each class contains different functions. If you want to use a specific function of a class within your program, then the package containing the functions needs to be included in your program using a keyword ‘import’.

Some examples of packages are:~
- `java.lang` 
- `java.io`
- `java.util`
- `java.net`

----

### Types of Java Programs

**Java stand-alone applications:** They are the programs written in Java to carry out certain tasks. These applications run directly by the Java interpreter. A standalone application should be delivered and installed on each computer before it is run.

**Java Applets:** they are the Java applications that are embedded inside HTML files and can be downloaded into a Java-capable browser.

----