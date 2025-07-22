# OOP
# Define OOP
"Object-oriented programming, or OOP, is a way of designing software by thinking in terms of 'objects' — which are like real-world entities. Each object contains its own data (called attributes) and the actions it can perform (called methods). So instead of just writing functions that process data separately, OOP combines both into one unit — making code more modular, reusable, and closer to how we model things in real life."
# What is the structure of object-oriented programming?
### 1. Class

- A **class** is a user-defined blueprint for creating objects.
- It defines the structure (attributes) and behavior (methods) common to all objects of that type.

#### Example:
``` java
class Car {
    String color; // Attribute
    void drive() { // Method
        System.out.println("Driving the car...");
    }
}
```
#### 2. Object
- An object is an instance of a class.
- It contains actual values and can use the methods defined in its class.
``` java
Car myCar = new Car();
myCar.color = "Red";
myCar.drive();
```

### 3. Attributes
- Attributes (also called fields or properties) hold the state or characteristics of an object.
- Defined inside the class.
Types of Attributes:

- Instance attributes – unique to each object.
- Class attributes – shared by all objects (using static keyword in Java).
``` java
class Car {
    String color; // instance attribute
    static int wheels = 4; // class attribute
}
```

### 4. Methods
- Methods define the behavior of an object.
- They are functions written inside a class and can access object attributes.
``` java
class Car {
    void drive() {
        System.out.println("The car is moving");
    }
}
