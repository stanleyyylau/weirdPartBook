# Section3 Types and operators

## Types and javascript


**Dynamic typing**: you don't tell the engine what type of data a variable holds, it figures it out while your code is running

Variables can hold different types of values because it's all figured out during execution.

Java is **static typing**



## Primitive types


six in total!!!

**Primitive type**: a tyoe of data that represents a single value.

That is, not an object(object is name/value pairs)

Undefined : represents lack of existence (you shouldn't set a variable to this)

Null: represents lack of existence (you can set a variable to this)

Boolean: true of false

Number: floating point number(there's always some decimals). unlike other programming languages, there's only one 'number' type... and it can make math weird.

String: a sequence of characters (both ''and "" can be used)

Symbol: used in ES6, we won't talk about this here...




## Operators

**Operator**: a special function that is syntactically differently

Generally,operators take two parameters and return one result.

```
var a = 3+4;
function +(a,b){
  return // add the two
}
```



## Operator precedence and associativity


**Operator precedence** : which opeatoro function gets called first

Functions are called in orders of precidence (higher precedence wins)

**Associativity**: what order operator functions get called in : left-to-right or right-to-left

when functions have the same precedence

**Download the pdf**




## Coercion

Coercion: converting a value from one type to another

This happens quite often in Javascript because it's dynamically typed.



## Comparison operators


Number(false)  what things will coerce to.

Number(true) 

```
console.log(3<2<1)  --> true
```

Number(null) --> 0


false == 0  --> true
null == 0  --> false
null < 1 -- > true
"" == 0  --> true

**Using triple equals 99% of the time!!!**


## Existence and Booleans

Boolean(undefined) --> false
Boolean(null)  --> false
Boolean("") --> false

The lack of existence




## Default Values

undefined || 'hello'  --> "hello"      returns whatever that can be coerce to true

Operators are functions that return value

function greet(name){
  name = name || '<Your name here>';
  console.log('Hello' + name);
}

greet('Tony');
greet();
greet(0);



## Framework aside


### Default values


window.libraryName = window.libraryName || "Lib 2";

