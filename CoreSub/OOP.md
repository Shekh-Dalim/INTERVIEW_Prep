🟢1 What is OOP 
```
   OOP stands for Object-Oriented Programming. It is a way of writing code by using "objects" 
   that have data (called properties) and functions (called methods). OOP makes code easier 
   to manage, reuse, and understand.
   ```

🟢2 What are the main Features of OOP?
```
   The main features of Object-Oriented Programming (OOP) are:

    *: Encapsulation – Wrapping data member and methods together, and hiding internal details.
    *: Abstraction   – Hiding complex logic and showing only the essential part.
    *: Inheritance   – One class can inherit features from another class.
    *: Polymorphism  – One method can perform different tasks based on the object.
    *: Class         – Class is a blueprint .
    *: Object        – Instance of class .
    *: Modularity    – Code is divided into small, reusable parts (modules).
    These features help in writing clean, reusable, and maintainable code.
    ```

🟢3 What are the advantage of OOP ?
```

   *: Code Reusability      – Using inheritance, we can reuse existing code.
   *: Easy Maintenance      – Code is modular, so it's easy to update or fix.
   *: Improved Productivity – Faster development with reusable and organized code.
   *: Better Data Security  – Encapsulation helps protect data from outside access.
   *: Real-World Modeling   – Objects represent real-world entities, making code easier to understand.
   *: Scalability           – Easy to manage and scale large projects.
   ```
   
🟢4 What is Structural Programming ?
```
   Structural Programming is a programming style where the code is written in a step-by-step manner 
   using functions, loops, and conditionals. It focuses on breaking a program into small, manageable
   parts to make it easier to read and debug.

   Key points:

   *: Uses sequence, selection (if/else), and loops (for/while).
   *: Follows a top-down approach.
   *: Example languages: C, Pascal.
   ```


🟢5 What is class?
```
    A class is a blueprint or template for creating objects, it defines the properties and behaviour 
    that the objects crate from the class will have.
    ```

🟢6  What do you mean by an object ?
```
    An object is an instance of a class. It is a real-world entity that has properties (data) and 
    behavior (methods) defined by the class.
    ```
    
🟢7  Is it always necessary to create objects from class ?
```
    If a class only has static methods or variables, we can access them directly using the class 
    name without creating an object. But if we want to use non-static methods or variables, then 
    we must create an object of the class.
    ```
    
🟢8  What is Constructor ?
```
    A constructor is a special method used to initialize objects of a class. It has the same name as 
    the class and does not have a return type(not even void). Constructors are automatically called 
    when an object is created.

    *: Used for initializing object properties when an object is created.
    *: A default constructor is provided if no constructor is explicitly defined.
    *: A parameterized constructor can be defined to initialize objects with specific values.
    ```

🟢9  List the various types of constructor ?
```
     
    *: Default constructor.
    *: Parameterized Constructor.
    *: Copy Constructor.
    *: Static Constructor.
    *: Private Constructor.
    ```

🟢10  What is a destructor ?
```
    A destructor is a special method that is automatically called when an object is destroyed or goes out 
    of scope. It is used to clean up resources allocated to the object, such as closing files, releasing 
    memory, or deallocating dynamic resources.

    *: Name: Destructor has the same name as the class, preceded by a tilde (~).
    *: No return type: Destructors do not have a return type or parameters.
    *: Automatic invocation: Automatically called when an object goes out of scope or is deleted.
    *: One per class: A class can have only one destructor.
    ```
    
🟢11  What is meant by a copy constructor ?
```
    A copy constructor is a special constructor in C++ used to create a new object by copying the values of an 
    existing object of the same class. It initializes a new object as a copy of an existing object.

    *: Name: The copy constructor has the same name as the class.
    *: Parameters: It takes a reference to an object of the same class as a parameter.
    *: Purpose: Used to initialize an object by copying data from another object.
    *: Automatic: The copy constructor is automatically called when a new object is created 
       from an existing object, such as during assignment or passing by value.
       ```
    
🟢12  Highlight the difference between a class and a structure.
```
    
    Access Specifiers:
        Class: By default, members are private.
        Structure: By default, members are public.

    Purpose:
        Class: Typically used for OOP (Object-Oriented Programming),to encapsulate data and behavior.
        Structure:  Primarily used to group related data (often for simple data storage), not necessarily for OOP.

    Inheritance:
        Class: Supports inheritance, enabling OOP principles.
        Structure: Does not support inheritance.

    Use in C++:
    Both can have functions, but classes are more commonly used for complex behaviors, while structures are 
    often used for simpler data grouping.
    ```

🟢13  Explain the concept of inheritance with an example?
```

    Inheritance is an poweful feature of OOP where a new class (derived class) inherits 
    properties and methods from an existing class (base class). This allows the derived class to reuse 
    code from the base class and extend or modify its behavior.

    *: The derived class inherits all non-private members (attributes and methods) of the base class.
    *: It promotes code reusability and helps create a hierarchy of classes.
    *: A class can inherit from one or more classes (single or multiple inheritance).
    ```
     
🟢14  What are the limitation of inheritance ?
```

    Tight Coupling:
        The child class is strongly dependent on the parent class. Any change in the parent class 
        can affect the child class, which may lead to issues.

    Less Flexibility:
        Once a class is inherited, it's hard to change its behavior without affecting other classes.
        It reduces code flexibility.

    Increases Complexity:
        Deep inheritance (many levels) can make the code harder to understand, maintain, and debug.

    Code Reuse Is Limited:
        Inheritance only allows reusing code from one class (single inheritance in many languages like Java), 
        not from multiple sources easily.

    Not Always the Right Choice:
        Inheritance is not suitable for all relationships. For example, "has-a" relationships 
        (like a car has an engine) should use composition instead of inheritance.
        ```
    
🟢15  What are the various types of Inheritance ?
```
    
    1: Single Inheritance
    2: Multiple Inheritance
    3: Multi level Inheritance
    1: Hierarchical Inheritance
    1: Hybrid Inheritance:
    ```
    
🟢16 What is the meaning of Hierarchical Inheritance ?
```

   Hierarchical Inheritance means when multiple child classes inherit from a single parent class.
   ```

🟢17 Distinguish between multiple and multilevel inheritance ?
```


Feature	                             Multiple Inheritance	                             Multilevel Inheritance
Definition	          A class inherits from two or more parent classes.      	A class inherits from a child class, which inherits from another class.

Structure	                    One child → many parents	                    One parent → one child → another child (chain-like)
   
Example (C++ style)	      class C : public A, public B {}	                     class C : public B {}; class B : public A {};

Use Case	         When a class needs features from multiple sources	         When features are passed through multiple levels  
```  

🟢18  How do you define hybrid iheritance ?
```

    Hybrid Inheritance is a combination of two or more types of inheritance, 
    such as multiple, multilevel, or hierarchical.
    ```
    
🟢19  What is Subclass ?
```
    A Subclass is a class that inherits properties and behaviors (methods) from another class, 
    which is called the Superclass (or Parent class).
    ```
     
🟢20  What is superclass ?
```
    A Superclass (also called Parent Class or Base Class) is the class whose properties and 
    methods are inherited by another class (called the subclass).
    ```

🟢21  What is mean by interface ?
```
    An interface in C++ is a contract that specifies a set of methods that a class must implement. 
    However, C++ doesn't have a direct keyword for interfaces like Java. Instead, we achieve 
    interfaces by using abstract classes with pure virtual functions.
    ```

🟢22  What is Polymorphism ?
```
    Polymorphism in C++ is the ability of a single function or method to work in different ways depending 
    on the object it is acting upon. It allows one interface to be used for different data types.

    There are two types of polymorphism in C++:
        Compile-time Polymorphism (Static Binding)
        Runtime Polymorphism (Dynamic Binding)
        ```

🟢23  What is meant by static Polymorphism ?
```
    The static polymorphism allows us to link a funtion with object during compilation . It can be 
    implemented by method overloading or operator overloading.
    ```

🟢24  What is meant by dynamic Polymorphism ?
```
   Dynamic Polymorphism allows us to link a function with an object during runtime (not at compile time).
   It is implemented using method overriding with the help of virtual functions.
   ```

🟢25  What is method overloading ? 
```
    Method Overloading means defining multiple functions with the same name in the same class, 
    but with different parameters (type, number, or order).
    ```

🟢26  What is method overriding ? 
```
    Method Overriding means redefining a base class method in a derived class using the same 
    method name, return type, and parameters.
    ```

🟢27  What is Operator overloading ?
```
    Operator Overloading means giving additional meaning to an existing operator (like +, -, *, etc.) so that it can work with user-defined data types (like classes or objects).

    It allows operators to be used just like they are used with basic types, but for custom objects.
    ```
    
🟢28  Different between Overloading and Overriding ?
```
    
    Feature	                                 Method Overloading	                                    Method Overriding

    Definition          Same method name with different parameters in the same class          Same method name, parameters, and return type in base and derived classes

    Purpose	            To perform similar tasks in different ways	                          To change or customize behavior of base class method

    Polymorphism Type	Compile-time Polymorphism (Static)	                                  Runtime Polymorphism (Dynamic)
    ```

🟢29  What is mean by data abstruction ? 
```
    Data Abstraction is the process of hiding the internal details of how something works and showing 
    only the essential features to the user.

    It helps in reducing complexity and increases code security by exposing only what is necessary.
    ```

🟢30  How can data abstruction be accomplished ?
```

    Data abstruction can be accomolished in OOP by using abstruct class and interfaces, which define
    abstruct methods that must be implemented by derived classes.

🟢31  What is mean by abstract class ?
    An Abstract class is made of abstruct methods . The abstract methods are only declare , however , 
    not implemented . when a subclass needs to use the methods, it needs to implement those method.
    ```

🟢32 Can you please elaborate on accesdd specifier ?    
```
    Access specifiers are special keywords that control the accessibility of method or classes etc. 
    They are also called access modifier and are used to achive encapsulation. 
    
    example: The keywords public, private , and protected are some examples of acess specifiers.
    ```

🟢33  How do you create an instance of an abstract class ?
```

    You cannot create an object (instance) of an abstract class directly in C++.
    Because an abstract class contains at least one pure virtual function, making it incomplete.

    You can use an abstract class in two ways:
        By creating a subclass (concrete class) and instantiating that.
        Using an anonymous class (lambda-style object).
        ```

🟢34  What is virtual funtion ?
```
    A virtual funtion is define in the parent class and may have definitions implemented.
    A Subclass can override these definition.
    ```

🟢35  What is a pure virtual funtion ?
```
    pure virtual function is a virtual function that does not have any definition in the base class 
    and must be overridden in any derived class.

    It makes the class abstract, meaning you cannot create objects of it directly.
    ```

🟢36  Distinguish between data abstraction and encapsulation.
```

    Aspect	              Data Abstraction	                                                  Encapsulation

    Definition	   Hiding internal implementation and showing only functionality	   Wrapping data and code into a single unit (like a class)

    Purpose	       To show only essential details to the user	                       To protect data from unauthorized access

    Focus	       Focuses on what an object does	                                   Focuses on how data is protected and maintained

    Achieved by	   Using abstract classes, interfaces, etc.	                           Using access specifiers (private, public, etc.)

    Example	       Using draw() method without knowing its internal logic	           Making age private and accessing it via getAge() method

    OOP Pillar	   Related to abstraction principle	                                   Related to encapsulation (information hiding)
    ```
    
🟢37  What are the differences between interfaces and abstract class ?
```

    Aspect	                        Abstract Class	                                                    Interface

    Definition	            A class with at least one pure virtual function	        A class with only pure virtual functions and no data

    Purpose	                Partial abstraction	                                    Full abstraction

    Function Types	        Can have both concrete and pure virtual                 functions	Can have only pure virtual functions

    Data Members	        Can have data members	                                Typically no data members (acts as a pure interface)

    Access Specifiers	    Can use public, private, protected sections             All members are public by design

    Constructor	            Can have constructors	                                Cannot have constructors (since no object is created)

    Multiple Inheritance	Supports single/multiple inheritance	                Used heavily with multiple inheritance

    Purpose                 For partial abstraction and code reuse	                For full abstraction (only define the contract/interface)
    ```

🟢38  What is final Variable ?
```

    A final variable is a variable whose value cannot be changed once assigned.
    It makes the variable constant — like a fixed value.
    ```
    
🟢39 What is mean by an Exception ?
```

   An exception is an unexpected error that occurs during the execution of a program, which disrupts 
   the normal flow of instructions.
   ```
    
🟢40  Define Exception Handling ?
```
    
    Exception handling is a way to detect and handle errors that occur during program execution,
    without crashing the program.
    ```
    
🟢41  Is an error the same as an exception ?
```

    No, an error is not the same as an exception.

    They are both problems that occur at runtime, but they are different in purpose and handling.
    ```
     
🟢42  What is a try-catch block ?
```

    A try-catch block is used in programming to handle exceptions (runtime errors) so the 
    program doesn't crash.
    ```


🟢43 Should you always use OOP ? Are there any limitations of OOP ?
```
    
   No, OOP (Object-Oriented Programming) is not always the best approach for every problem. 
   While it has many advantages, it may not be suitable for every scenario. 
   ```

🟢44 What are the limitation of OOP ?
```
   
    Complexity:                OOP can add unnecessary complexity for simple problems with concepts like inheritance and polymorphism.

    Performance Overhead:      Object creation and method calls (especially virtual functions) can reduce performance compared to procedural programming.

    Steep Learning Curve:      Mastering OOP concepts can be challenging for beginners, leading to a longer initial development process.

    Not Always the Best Fit:   OOP may not be efficient for simple or data-centric tasks, where procedural or functional programming works better.

    Increased Code Size:       OOP often results in larger code due to classes and methods, which may be unnecessary for simpler programs.
    ```
    
🟢45 How does c++ programming language support polymorphism ?
```
   
   C++ supports polymorphism primarily through two mechanisms:
        1: Compile-time Polymorphism (Static Binding).
        2: Run-time Polymorphism (Dynamic Binding):
        ```

🟢46  What is method hiding in C++?
```
    Method hiding occurs when a method in a derived class has the same name as a method in the base class. 
    This is not an overriding situation because the base class method doesn't have the virtual keyword, 
    and the method in the derived class hides the base class method.
    ```

🟢47 What is the difference between shallow copy and deep copy in C++?    
```

   Shallow Copy: 
   A shallow copy creates a new object, but does not create copies of the objects that are pointed 
   to by pointers in the original object. It simply copies the pointers.

   Deep Copy: 
   A deep copy creates a new object and copies the data from the original object. If the object 
   contains pointers, the deep copy will also allocate new memory for the pointers and copy the 
   data they point to.
   ```

🟢48 What is the difference between 'new' and 'malloc' in C++?
```

   new: 
   A C++ operator that allocates memory for a single object or array and automatically calls the 
   constructor of the object. It returns a pointer to the allocated memory.

   malloc: 
   A C function that allocates a block of memory but does not initialize the memory or call 
   a constructor. It returns a void* pointer, which must be typecast to the desired type.   
   ```
           
🟢49 What is a 'virtual destructor'?
```
    A virtual destructor ensures that when an object is deleted through a base class pointer, 
    the destructor of the derived class is called, allowing proper cleanup of resources. 
    ```


🟢50 What is the purpose of 'explicit' keyword in C++?
```
   The explicit keyword is used to prevent the compiler from performing implicit type conversions for constructors. 
   It ensures that constructors are called only when the arguments are explicitly provided.
   ```

🟢51 What is the difference between 'protected' and 'private' access specifiers?
```

    protected: 
    Members are accessible within the same class, derived classes, and friends of the class.

    private: 
    Members are only accessible within the same class, not by derived classes.
    ```
     
🟢52  What is a finally block ?  used only in JAVA not IN C++
🟢53  What is the method 'finslize' used for ?  used only in JAVA not IN C++
🟢54 What is Garbage collection, and how does it work ?  used only in JAVA not IN C++