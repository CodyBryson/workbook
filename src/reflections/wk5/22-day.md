# Day Twenty-two Reflection
__01/13/2021__

## What is a sub-document?

Subdocuments are documents nested within other documents. A usual indicator is if a schema is nested within another schema.
## When might you use a sub-document?

You can use sub-documents when you want to append additional properties to a schema, or add object properties to an existing object. You can also nest a schema within another schema in order to better separate your data.

## How do you add a collection of sub-documents and how do you edit them?

The easiest way to add a collection of sub-documents is to use a findone method to find a document. Use a get to retrieve the array. You then edit the array and save it back to the document. Just like any array, a push method can be used to add things to an existing array.

## Afternoon Project

https://github.com/CodyBryson/da-planets