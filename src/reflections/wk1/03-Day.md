# Day Two Reflection
__12/01/2020__

## What is your favorite tip that you think is the most beneficial to improving your design?

A pseudo-class is a specific class you can attach to an element in order to garner a unique effect from it. Examples include changing color of an object when hovering over it, checking a box, or changing the mouse pointer to a clicker when over a button. The most common pseudo-classes I can see using are changing an element's color on mouse over, changing the cursor over a button, and checking boxes.
## Compile a couple resources taht you think might be helpful when trying to review examples of good design ideas.

Specificity is like the order of operations for CSS. In CSS, specificity is based off a heiarchy system (0,0,0) where the higher the number, the more important it is considered when applying your CSS. For example if a box is colored green with a specificity of (0,1,0) and after, that same box is colored red with a specificity of (0,0,1), the box will still be green. Specificity tends to default to higher values the more nested the element that the css is applying changes to.

You can take advantage of this in a number of ways, but the most likely avenue is when you want to change one element of many of the same type. For instance you have twenty red boxes. On one of those boxes you want the color to be green. Instead of having to color all of the boxes individually, you can add a CSS pseudo-class to that one specific box with a higher specificity than the others with the color green.

## How do you think good design influences people when visiting a website and what sorts of things could you convey through design alone?

The !important feature is a feature that rockets an element's specificity up to a thousand. This makes it so that the rule in place is always in effect. An issue that can come from this are conflicting rules in other frameworks, such as bootstrap. Also, if a designer is working on your code and attempting to change the color of something, they may become frustrated having to comb through your code to find the !important features. This can also cascade to other issues and overall just convolute your specificity throughout the entire application.