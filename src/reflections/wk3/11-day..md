# Day Eleven Reflection
__12/14/2020__

## How to solve problems using exports.

Exports solves the issue of multiple script tags in the html. Instead of linking several different js tags, therefore slowing your page down, you can export different sets of code to the main.js and use that script tag only. 
## What is the difference between export and export default?

Export exports the code as is and must be imported as is. If you are assigning an alias to the data you are importing, you must export the code as default or else you will receive a syntax error.

## A reason to use the module system.

The module system has several benefits. One, it cuts down on multiple script tags in your html, therefore causing slow web pages. It also keeps some things hidden that you might not want others to be able to see. It is easier to debug your code as well.