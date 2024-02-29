In JavaScript, a class is a blueprint for creating objects with similar properties and methods. It provides a way to define a particular type of object and organize its behavior. Classes are introduced in ECMAScript 2015 (ES6) and provide syntactical sugar over the existing prototype-based inheritance model in JavaScript.

Here's a basic example of a class definition in JavaScript:
class Car {
  constructor(brand, model) {
    this.brand = brand;
    this.model = model;
  }

  drive() {
    console.log(`The ${this.brand} ${this.model} is driving.`);
  }
}

// Creating instances of the Car class
const myCar = new Car('Toyota', 'Camry');
const anotherCar = new Car('Honda', 'Accord');

// Calling methods on the instances
myCar.drive(); // Output: The Toyota Camry is driving.
anotherCar.drive(); // Output: The Honda Accord is driving.
In this example, Car is a class with a constructor method (constructor) for initializing objects created with the class, and a method (drive) for defining behaviors. Instances of the Car class (myCar and anotherCar) can be created using the new keyword, and methods can be called on these instances.

JavaScript classes are syntactical sugar over JavaScript's existing prototype-based inheritance, providing a more familiar and cleaner syntax for defining object-oriented programming structures. Under the hood, classes still use prototypes and constructor functions to achieve inheritance and object creation.