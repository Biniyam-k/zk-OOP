## Java Constructors
Java constructors or constructors in Java is a terminology been used to construct something in our programs. 
A constructor in Java is a special method that is used to initialize objects.
The constructor is called when an object of a class is created. It can be used to set initial values for object attributes.

A constructor in Java is similar to a method that is invoked when an object of the class is created.
Unlike Java methods, a constructor has the same name as that of the class and does not have any return type. 
At the time of calling the constructor, memory for the object is allocated in the memory.
It is a special type of method which is used to initialize the object. 
Every time an object is created using the new() keyword, at least one constructor is called.

For example,

```
class Main {
  private String name;

  // constructor
  Main() {
    System.out.println("Constructor Called:");
    name = "ACT JAVA";
  }

  public static void main(String[] args) {

    // constructor is invoked while
    // creating an object of the Main class
    Main obj = new Main();
    System.out.println("The name is " + obj.name);
  }
}
```

