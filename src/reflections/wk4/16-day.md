# Day Sixteen Reflection
__01/04/2021__

## Callback hell! What are the signs and how do you protect yourself from it?

Callback hell occurs when a single function tries to do too many things. The function becomes bloated and ends up being a mess to read. If at the end of the function you see several, )} or }, chances are you are teetering if not already in callback hell.
## What asychronous is and what callbacks do.

Async is telling a function that it does not need to return its results right away. This prevents bottleneck and allows other functions to run while the async function works. Callbacks use async in order to perform a function at a later time.

## Three Ways to Prevent Callback Hell.

Three ways to prevent callback hell are keeping your code shallow, using a module, and handling all of your errors. Shallow code improves readability, allowing others to follow your work without as much issue as many lines of code or a function. A module helps to break apart your code into a more readable platform. Handling all of your errors allows you to pinpoint things before they get lost in the shuffle. 

## Afternoon Project

https://github.com/CodyBryson/OpenTrivia