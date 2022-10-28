# OOP
Introduction to JAVA OOP

Object-oriented programming (OOP) is a style of programming characterized by the identification of classes of objects closely linked with the methods (functions) with which they are associated. It also includes ideas of inheritance of attributes and methods. It is a technique based on a mathematical discipline, called “abstract data types,” for storing data with the procedures needed to process that data. OOP offers the potential to evolve programming to a higher level of abstraction.

Object Oriented programming (OOP) is a programming paradigm that relies on the concept of classes and objects. It is used to structure a software program into simple, reusable pieces of code blueprints (usually called classes), which are used to create individual instances of objects.

Object-oriented programming (OOP) is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.

The dictionary meaning of an object is "an entity that exists in the real world", and oriented means "interested in a particular kind of thing or entity".
In basic terms, OOP is a programming pattern that is built around objects or entities, so it's called object-oriented programming

OOP focuses on the objects that developers want to manipulate rather than the logic required to manipulate them. This approach to programming is well-suited for programs that are large, complex and actively updated or maintained. This includes programs for manufacturing and design, as well as mobile applications;

![alt text](https://www.freecodecamp.org/news/content/images/size/w1600/2022/09/OOP.png)


## Class 
In a nutshell, classes are essentially user defined data types. Classes are where we create a blueprint for the structure of methods and attributes. Individual objects are instantiated, or created from this blueprint.

A class is a blueprint or template of an object. It is a user-defined data type. Inside a class, we define variables, constants, member functions, and other functionality. it binds data and functions together in a single unit. It does not consume memory at run time.
 - Note that classes are not considered as a data structure. It is a logical entity. It is the best example of data binding. 
 - Note that a class can exist without an object but vice-versa is not possible.-


## Object

These are instances of a class with specifically defined data. When a class is defined initially, the description is the only object that is defined.
An object is a real-world entity that has attributes, behavior, and properties. It is referred to as an instance of the class. It contains member functions, variables that we have defined in the class. It occupies space in the memory. Different objects have different states or attributes, and behaviors.

At the point of creation of a class, the description is the first object to be defined. An instance of a class exists in an object. Notably, the system does not allocate any memory space when a class is specified, but it’s allocated when it is instantiated, i.e., when an object is formed. Real-world things have state and behavior in common, a pair of features. An object conceals its behavior through methods and keeps its information in attributes.

## Methods 

These are functions that are defined inside a class that describe the behavior of an object. They are useful for re-usability or keeping functionality encapsulated inside one object at a time. Code re-usability is a great benefit when debugging.


## Attributes 

are defined in the class template and represent the state of an object. Objects will have data stored in the attributes field. Class attributes belong to the class itself
 and represent the state of an object. Objects contain data stored in the attribute field.


![alt text](https://www.imaginarycloud.com/blog/content/images/2021/07/OOP_4p.png)

## Inheritance

Inheritance allows classes to inherit features of other classes. Put another way, parent classes extend attributes and behaviors to child classes. Inheritance supports reusability.

If basic attributes and behaviors are defined in a parent class, child classes can be created extending the functionality of the parent class, and adding additional attributes and behaviors.

Relationships and subclasses between objects can be assigned, enabling developers to reuse common logic while still maintaining a unique hierarchy. This property of OOP forces a more thorough data analysis, reduces development time and ensures a higher level of accuracy.

The benefits of inheritance are programs can create a generic parent class, and then create more specific child classes as needed. This simplifies overall programming, because instead of recreating the structure of the Parent class multiple times, child classes automatically gain access to functionalities within their parent class.

## Abstraction

Abstraction means that the user interacts with only selected attributes and methods of an object. Abstraction uses simplified, high level tools, to access a complex object.

    Using simple things to represent complexity
    Hide complex details from user

Abstraction is using simple classes to represent complexity. Abstraction is an extension of encapsulation. For example, you don’t have to know all the details of how the engine works to drive a car.

A driver only uses a small selection of tools: like gas pedal, brake, steering wheel, blinker. The engineering is hidden from the driver. To make a car work, a lot of pieces have to work under the hood, but exposing that information to the driver would be a dangerous distraction


A well-designed module hides all of its implementation details and cleanly separates its interface from its implementation. These modules then communicate with each other only through the interfaces. This concept is supported with the help of Abstraction in Java.

The meaning of the word “Abstraction”, in general words, is the process of working with ideas rather than their implementation.

For example, consider the example of an email, the user does not know about the complex details such as what happens just after sending an email, which protocol is used by the server to send the message.

Therefore, we just need to mention the address of the receiver, type the content and click the send button.

This is basically called Abstraction in which the complex details are being hidden from the users.

Similarly, in Object-oriented programming, abstraction is a process of providing functionality to the users by hiding its implementation details from them. In other words, the user will have just the knowledge of what an entity is doing instead of its internal working.

## Encapsulation

This is the concept that binds data together. Functions manipulate the info and keep it safe. No direct access is granted to the info in case it's hidden. If you wish to gain access to the info, you need to interact with the article in charge of the info.

If you're employed in a company, chances are high that you've had experience with encapsulation.

Think about a human resources department. The human resources staff members encapsulate (hide) the data about employees. They determine how this data will be used and manipulated. Any request for the worker data or request to update the info must be routed through them.

By encapsulating data, you make the information of your system safer and more reliable. You're also able monitor how the information is being accessed and what operations are performed on it. This makes program maintenance easier and simplifies the debugging process.

In other words, we can define it as Encapsulation is the wrapping up of data and functions (methods that operate on the data) into a single unit (called class).

There is a prohibition for direct access to the data. Functions (that combine with the data) are the only way to access data. These functions are the member functions or methods in Java. It basically creates a shield due to which the code or data cannot be accessed outside the shield.

If you want to read data items in an object, you call the member function in the object. It will read the data item from the function and return the value to you. You can’t access the data directly using the object. The data is hidden, so it is kept protected and safe from accidental alteration.


## Polymorphism

The word Polymorphism can be broken into two words – ‘poly’ means ‘many’ and ‘morph’ means ‘forms’. So, polymorphism means many forms.

Polymorphism is the ability for a data or message to be processed in more than one form. It is a concept by which a single operation can be performed in multiple different ways.

Polymorphism is the concept that allows an object of a class to behave differently in response to a message or action.

This is the power of two different objects to reply to one form. The program will determine which usage is critical for every execution of the thing from the parent class which reduces code duplication. It also allows different kinds of objects to interact with the same interface.

The virtue by which the same action can be performed by objects of different classes and each object responds in a different way depending on its class is called Polymorphism.






