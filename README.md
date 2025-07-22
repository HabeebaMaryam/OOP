# OOP
# Define OOP
"Object-oriented programming, or OOP, is a way of designing software by thinking in terms of 'objects' — which are like real-world entities. Each object contains its own data (called attributes) and the actions it can perform (called methods). So instead of just writing functions that process data separately, OOP combines both into one unit — making code more modular, reusable, and closer to how we model things in real life."
# What is the structure of object-oriented programming?
### 1. Class

- A **class** is a user-defined blueprint for creating objects.
- It defines the structure (attributes) and behavior (methods) common to all objects of that type.

#### Example:

class Car {
    String color; // Attribute
    void drive() { // Method
        System.out.println("Driving the car...");
    }
}

#### Object
- An object is an instance of a class.
- It contains actual values and can use the methods defined in its class.
Car myCar = new Car();
myCar.color = "Red";
myCar.drive();

### Attributes
- Attributes (also called fields or properties) hold the state or characteristics of an object.
- Defined inside the class.
- Types of Attributes:

- Instance attributes – unique to each object.
- Class attributes – shared by all objects (using static keyword in Java).
