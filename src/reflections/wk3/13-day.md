# Day Thirteen Reflection
__12/16/2020__

## Two common operations that are set in the handler.

The get and the set operators are two operations that can be performed on an object. Get is an operation on the object that can get values of the key. The set operator operates on the object to set the value of an object.
## Things to make sure you do with every Get to make sure the value does not become undefined.

The get operatorer takes in two parameters, the object and the property being accessed. To make sure that every Get does not return a value that is undefined, you need to set a get trap. A trap is something that triggers whenever an object property is being accessed. 

## The benefits of the proxy object.

A proxy object creates a copy of an object that can have unique handlers attached. With a proxy object, you can set custom traps in order to prevent the user from accessing the properties of the initial object. 