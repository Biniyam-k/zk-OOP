
## Java Method Overloading

In Java, two or more methods may have the same name if they differ in parameters (different number of parameters, different types of parameters, or both). These methods are called overloaded methods and this feature is called method overloading. For example:

```
void methodName() { ... }
void methodName(int a) { ... }
float methodName(double a) { ... }
float methodName(int a, float b) { ... }

```

## Note:
The return types of the above methods are not the same. 
It is because method overloading is not associated with return types.
Overloaded methods may have the same or different return types, but they must differ in parameters.

## Important Points
Two or more methods can have the same name inside the same class if they accept different arguments. This feature is known as method overloading.
Method overloading is achieved by either:
changing the number of arguments.
or changing the data type of arguments.
It is not method overloading if we only change the return type of methods. There must be differences in the number of parameters.
