# Day Six Reflection
__12/07/2020__

## How would you define scope in Java Script?

Scope defines where you can use a variable. Variables are either globally scoped, meaning they are declared at the top and affect all areas of the script outside of a function. Or they are locally scoped, where they exist within the function itself.
## Hoist the sails me hardies, ho ho!

Hoisting is where variable delcarations are brought to the top of the function when running. So even if you declare the variable at the bottom of the function, it will be read first before the rest of the function.

## Let, Const, and Var: When and where to use these declarations.

You can use Var declarations when you need to re-define and update the variable within the function. You can use the Let declaration when you need to update the variable, but not re-define it. And finally you can use the Const declaration when you neither need to re-define or update a variable and need a variable to remain the same throughout the function.