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