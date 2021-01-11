# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Asynchronous code, unlike synchronus code does not happen right away. This is done using callbacks. Asynchronous code,in this way, allows us to "skip" functions that take time such as speaking to databases and still render things to the DOM for the user.  
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is ususually written as ProxyState.on('event') with 'event' being the event to listen for. These are used in the code to say, when this event occurs do something.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The 'O' in 'SOLID' principles represents the Open/closed principle. It says that a software module, class, or method should be open for extension but closed for modification.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a prepend to a line of code that allows it to return something later. It preventes the application from getting stuck on a function that could take time to resolve.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is an object with three states: pending, resolved, and rejected. You can capture an error from a promise using a try/catch.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Get, Post, and Put.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The Service.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation is used to keep methods and code hidden from the user. It is also used to organize code in a more readable manner.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
resolved
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A 500 error is an internal server error response code that server puts out when a condition prvented it from fulfilling a request.
```