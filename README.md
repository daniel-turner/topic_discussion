#Dev League Topics

##Javascript
###Dynamic Typing
I thought this would bother me a lot coming from strongly-typed languages. So far, however, it's been uncomfortable at times, but mostly enjoyable!

When you name a bit of data, the name becomes a reference to that data making what we call a variable. Every variable has a type which tells whether it is a number (and sometimes what kind of number it is), a string of text, or more complex but still elemental types like arrays and objects. This tells the interpreter (that processes the javascript code) how to handle the data that the variable references. In strictly-typed languages, a variable's type is always strictly defined. You can change the type if you want (sometimes!), but every variable has an explicitly defined type which is enforced at all times. In a dynamically-typed language like javascript, on the other hand, the type of the variable is often inferred from the data it references, or contextually, in how it is used in functions.

###Arrays

An array is a particular kind of type in javascript. Think of it as an ordered list of things, and each thing in the list has an index number that tells what position that thing has in the list. For example, say we have a variable named "cars". We can declare it as

$ var cars;

The "var" tells the interpreter that you are declaring a variable.

Now we set the cars variable to equal an array of string types containing car names. The notation for an array is "[" to begin the array and "]" to finish it.

$ cars = ["Ford","Honda","BMW","KIA"];

We can then access individual items in the array by their index number thusly:

$ cars[0]; // "Ford"
$ cars[1]; // "Honda"
$ cars[2]; // "BMW"
$ cars[3]; // "KIA"

Note that array indices are "0-based", meaning the first item index is 0, not 1.

In addition to being a container for an ordered list of things, array types provide a variety of properties and methods for getting information about the list, searching it, and changing it. For example,

$ cars.length; // returns 4, the number of items in the array.
$ cars.indexOf("Ford"); // returns "0", the index of the "Ford" string in the array
$ cars.push("Mini"); // adds the string "Mini" at the end of the array
$ cars.pop(); // removes the last item of the array

It may seem simple, but arrays are extremely useful and ubiquitous!


###Objects

###Functions and Closures
Between these topics and scope, I feel like I have a workable, journeyman understanding, but the wizardry that I know that's possible with some of this is still well beyond me.
###Scope
See above.
###Development Environment
I've gotten a lot more comfortable with the environment.