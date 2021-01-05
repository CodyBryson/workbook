# Day Seventeen Reflection
__01/05/2021__

## The three states of a promise.

The Observer Pattern helps to solve the issue of updating the DOM in response to certain events. It allows you to create re-usable code that creates solutiosn for your specific needs that flows in a one-way stream. 
## How promises help to prevent callback hell.

The three mechanisms of the Observer Pattern are the subscribe method, the unsubscribe method, and the broadcast method. The subscribe method adds events to the pattern. The unsubscribe method removes evens from the pattern. The broadcast method calls events from the pattern. 

## The differences between .then() and .catch().

The Observer Pattern allows us to have a reactive way of updating the DOM based on user input. The subscribe method receives the user input and adds those events based on your code. If things are removed, the events are unsubscribed as they are no longer needed and finally broadcasted back to the user by updating the DOM. By using proxy objects, a instance of an object and the properties necessary is created and changed without affecting the initial object. 