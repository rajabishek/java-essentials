# Strongly typed
Java is a strongly typed language. This means that every variable and every expression in Java has a specific type. There are no automatic coercions or conversions of conflicting types as in some languages. A type compatabilty check is performed everytime a variable assigment is being made or every time an argument is passed to a method. Any mismatch in types are reported as compile time errors and are prevented as early in the development process itself. This is what makes Java highly safe and robust in nature.

# Primitive types
There are only 8 primitive types in Java. These include ```java byte```, ```java short```, ```java int```, ```java long```, ```java float```, ```java double```, ```java char``` and ```java boolean```. The primitive types are also called as simple types. In some languages even the basic data types are modelled as objects of some class for better clarity and code consistency. But in Java the primitive types are not objects of some class. They are similar to simple types that are found in most other non–object-oriented languages. The main reason for this choice is to improve performance and flexibility. In some languages such a C or C++ the size of a variable of a primitive type can vary based on the platform in which the program is compiled. Since Java tries to achieve portability the size of the data type is always fixed and it is independant of the platform. For example a variable of type ```java byte``` is always 8 bits in size regardless of the plaform.

# Byte
```java byte``` is the smallest integer type in Java. This is a signed 8-bit type that has a range from –128 to 127. Infact all integer types in Java are signed in nature. There are no unsigned integer data types in Java. The designers of Java felt that unsigned integers were unnecessary. Variable of the ```java byte ``` data type are useful when working with a stream of data from a network or a file. For example, the following declares a byte variables called data.
```java 
byte data;
```

# Short
```java short``` is a signed 16-bit type having range from –32,768 to 32,767. It is probably the least- used Java type. The following declares a variable of ```java short``` datatype called a.
```java 
short a;
```

