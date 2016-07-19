# Section6: Building Objects



## Function Constructors

Function constructors, 'new', and the history of javascript

```
var john = new Person(); //java developer used to do this
```

new changes what the ```this``` points to

function constructor: a function used to construct an object

function construcors are just functions

new create an empty object

new ooperator crate an brand new empty object and the function that's being called to construbto it is adding property and methods to it.





## Function constructors and prototype


Ptototype of an object and the prototype property of an object is not the same!

in good js code, properties are sitting inside function, becuase we need to change that, but methods, are sitting on the prototype.




## Danger: new and functions

if you forget to use new, it will call the function, since it does not return anything, it will return undefined

convention: capital letter for functions intentd to be constructor

**Capital**





## Built-in function constructors

var a = new Number(3)

a -->   Number{[primitivaValue]:3}



Look like you're creating primitive, but it's actully objects with methods

"John".length   the javascript engine boxed it inside of a string object which has length propery and mathoeds

Js will autoly convert string to an object, but not number to an object






## Danger: built-in function constrctors



var a = 3;
var b = new Number(3)

a == b  --> true
a === b --> false

**You are creating object, not just primitives!!!**


moment.js






## Danger: array and for ..  in


why you can use [] to grab array

like object

arrays are objects in javascript and their properties are added to it





## Object.create and pure prototypal inheritance


var john = Object.create(person);

it's simple and powerful, use this all the time, it's pure prototypal


**polyfill**: code that adds feature which the engine may lack.


unary and binary ternary operate taking one , two and three

**try thinking purely prototypal!!!**




## ES6 and classes



appreate prototupal inheritance!!!

don't mimic other languages!!!

....


Ayntacic sugar: a different way to type something taht doesn't change how it works under the hood







