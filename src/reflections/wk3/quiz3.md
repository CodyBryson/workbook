# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The four Pillars of Ojbect Oriented Programming are Encapsulation, Abstraction, Inheritance, and Polymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
property(this.name)
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is a way of bundling data and objects that act on that data from being accessed outside of the bundle. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single-responsibility principle.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class describes a data type while an instance of a class is an object of the data type that exists in memory.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an object that acts like the real service object in a program. It can be changed and manipulated without affecting the real service object. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the MVC pattern is to prevent multiple script tags from slowing down the DOM, as well as utilizing clean reusable code that can creates solutions to user input without affecting the code itself.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller receives input by watching values. It sends commands to the service in order to perform a function. It receives instructions from the appstate and then draws back to the dom.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service performs the business logic and functions and sets data to the app state.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the model holds the templates of objects as well as classes to be used in the service.
```

