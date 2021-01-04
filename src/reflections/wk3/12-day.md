# Day Twelve Reflection
__12/15/2020__

## What does encapsulation do?

Encapsulation bundles data and methods that act on that data restricted from outside the bundle. The only way to change the state of an object, which stories its state privately, you must call a method on that object. 
## What are the problems with closures and the underscore prefix?

closures and th eunderscore prefix can cause breaking changes. As underscore prefixes are considered methods that are changed only internally, they do not consider changing or deleting them to be a breaking change. Additionally, new developers are not aware of the underscore prefix and use their properties anyway. They also are not cyber security safe, as they give hackers more attack surface to exploit.

## Creating private variables in an ES6 class and why you would do this.

Creating private variables in an ES6 class allows you to create a new variable equal to the new class and have access to all of its variables without having to create the variables again. In this way, you can use the code in multiple instances without having to rewrite it, and then variables still remain encapsulated within the class itself.