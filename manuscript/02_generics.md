> - Generics are an integral part of Java programming.
> - Through the use of generics, it is possible to create classes, interfaces, and methods that will work in a type-safe manner with various kinds of data.
> - Many algorithms are logically the same no matter what type of data they are being applied to. For example, the mechanism that supports a stack is the same whether that stack is storing items of type `Integer`, `String`, `Object`, or `Thread`.
> - With generics, you can define an algorithm once, independently of any specific type of data, and then apply that algorithm to a wide variety of data types without any additional effort.
> - Collections Framework is one feature of Java that has been most significantly affected by generics.
> - The Collections Framework defines several classes, such as lists and maps, that manage collections. A collection is a group of objects.
> - The collection classes have always been able to work with any type of object. The benefit that generics added is that the collection classes can now be used with complete type safety.
> - At its core, the term generics means parameterized types.
> - They enable you to create classes, interfaces, and methods in which the type of data upon which they operate is specified as a parameter. Using generics, it is possible to create a single class, for example, that automatically works with different types of data.
> - A class, interface, or method that operates on a parameterized type is called generic, as in generic class or generic method.
> - Java has always given you the ability to create generalized classes, interfaces, and methods by operating through references of type `Object`. Because `Object` is the superclass of all other classes, an `Object` reference can refer to any type object. Thus, in pre-generics code, generalized classes, interfaces, and methods used `Object` references to operate on various types of objects. The problem was that they could not do so with type safety.