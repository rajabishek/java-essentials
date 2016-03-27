# Strongly typed
Java is a strongly typed language. This means that every variable and every expression in Java has a specific type. There are no automatic coercions or conversions of conflicting types as in some languages. A type compatabilty check is performed everytime a variable assigment is being made or every time an argument is passed to a method. Any mismatch in types are reported as compile time errors and are prevented as early in the development process itself. This is what makes Java highly safe and robust in nature.

# Primitive types
There are only 8 primitive types in Java. These include ```java byte```, ```java short```, ```java int```, ```java long```, ```java float```, ```java double```, ```java char``` and ```java boolean```. The primitive types are also called as simple types. In some languages even the basic data types are modelled as objects of some class for better clarity and code consistency. But in Java the primitive types are not objects of some class. They are similar to simple types that are found in most other non–object-oriented languages. The main reason for this choice is to improve performance and flexibility. In some languages such a C or C++ the size of a variable of a primitive type can vary based on the platform in which the program is compiled. Since Java tries to achieve portability the size of the data type is always fixed and it is independant of the platform. For example a variable of type ```java byte``` is always 8 bits in size regardless of the plaform.

# byte
```java byte``` is the smallest integer type in Java. This is a signed 8-bit type that has a range from –128 to 127. Infact all integer types in Java are signed in nature. There are no unsigned integer data types in Java. The designers of Java felt that unsigned integers were unnecessary. Variable of the ```java byte ``` data type are useful when working with a stream of data from a network or a file. For example, the following declares a byte variables called data.
```java 
byte data;
```

# short
```java short``` is a signed 16-bit type having range from –32,768 to 32,767. It is probably the least- used Java type. The following declares a variable of ```java short``` datatype called a.
```java 
short a;
```

# int
```java int``` is the most commonly used integer type in Java. This is a signed 32-bit type that has a range from –2,147,483,648 to 2,147,483,647. They are commonly used for the control loops and to index arrays. Lets say we have a smaller array to index, usually our assumption would be that the usage of ```java byte ``` or ```java short``` datatype would be more efficient, but this is not the case. The reason is that whenever byte and short values are used in an expression, they are promoted to ```java int``` when the expression is evaluated, this is called as type promotion. Therefore, ```java int``` is often the best choice when an integer is needed. The following declares a variable of ```java int``` datatype called count.
```java
int count;
```
# long
```java long``` is a signed 64-bit type and is useful for those scenarios where an ```java int``` type is not large enough. The range of a ```java long``` is high and  makes it useful when large integers are needed for manupulation. The following declares a variable of ```java long``` datatype called bigNumber.
```java
long bigNumber;
```

# float
```java float``` is the single precision floating point type in Java that uses 32 bits of storage. Variables of type float are useful when you need a fractional component, but don’t require a large degree of precision. The following declares a variable of ```java float``` datatype called b.
```java
float b;
```

# double
```java double``` is the double precision floating point type in Java that uses 64 bits of storage. When you need to maintain accuracy over many iterative calculations, or are manipulating large-valued numbers, ```java double``` is the best choice. All math function in java like ```java sin()```, ```java cos()```, ```java sqrt()``` return ```java double``` values. The following declares a variable of ```java double``` datatype called pi.
```java
double pi = 3.1416;
```

# char
Java uses Unicode to represent characters. Unicode defines a fully international character set that can represent all of the characters found in all human languages. ```java char``` is 16 bits in size with a range from 0 to 65,536. There are no negative chars. The following declares a variable of ```java char``` datatype called ch1. The symbols can also be represented in unicode formar. We have to prefix the code value with \u while defining the character.
```java
char ch1 = 'A';
```

