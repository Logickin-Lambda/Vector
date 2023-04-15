# Vector for pixilang

Pixilang is an interesting language because it is not based on common programming language like having the concept of structure and objects, but it is a "pixel Orientated" language which most of the stuff are based on pixels, making the language good for small graphical and audio experiment and application. Despite being a C like langaues, it has no basic data structures which we are familiar with other common languages. One of them is the Vector (or ArrayList) which is commonly used for creating an array with an unknown size during runtime.

This experimental pixi-library provide a more idiometic way to make the use of containers feeling more like a vector, including:
- construct a new vector
- push and pop items at the end of the vector
- insert and delete middle items by index
- find the index of an items in a vector

To understand how to use the library, a demo is prepared. To run the demo, simply run it by picking the file in the pixilang

Changelog:

0.2.0:
Vector functions can now be accessed using dot operator, but with a catch which you have to specify the object in the parameter.
