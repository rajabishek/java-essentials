A simple definition of a class is given below.
```java
class ClassName {
    String var1;
    int var2;
    
    String getVariable1() {
        return var1;
    }
}
```
> - Class is a template for an object, and an object is an instance of a class. Class essentially defines a new data type.
> - Words object and instance used interchangeably.
> - Classes contain both data and associated code.
> - The data, or variables, defined within a class without the static keyword are called instance variables because each instance of the class (that is, each object of the class) contains its own copy of these variables thus making the data for one object separate and unique from the data of another.
> - The code is contained within methods.
> - Collectively, the methods and variables defined within a class are called members of the class.

```java
class Box {
    double width;
    double height;
    double depth;
}
Box box; //declare a variable that can refer to an instance of Box in memory
box = new Box(); //dynamically allocates memory for a new instance of Box and return the reference
```
The box variable is pointing to the newly created Box instance in memory. Each time we do a `new Box()` we create a new instance in memory and a refrence to it is returned.
```java
box = new Box();
```
In the above code the existing box variable is made to point to the newly created instance and the previously created instance now doesn't have a variable refrencing it and therefore becomes eligible for garbage collection.
> - A java file can have atmost have only 1 public class.
> - The java file name must exactly match the name of the public class present in it.
> - The class where the entry must start must have the `public static void main(String[] args)` method declaration.
> - Instance variable can be accessed using the dot syntax, i.e `object.data`.
> - An object reference in java is similar to a memory pointer in C/C++, but the main difference and the key to Java’s safety is that you cannot manipulate references as you can with actual pointers, this you cannot cause an object reference to point to an arbitrary memory location or manipulate it like an integer.
> - When a member is declared static, it can be accessed before any objects of its class are created, and without reference to any object, like `className.data` or `className.methodName()` where `data` and `methodName` are `static` members.
> - `main(String[] args)` is declared as `static` because it must be called before any objects exist.