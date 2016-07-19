# Section5: Object-oriented Javascript




## Classical or proptopal


**Inheritance**: one object gets access to the properties and methods of anothe robject


**Classical inheritance**: 

**Prototypal inheritance**: Simple. flexibal. extensible. easy to understand





## Understanding the propotopal

**All objects includeing function object has a proto property**

dont overthink it, you don't have to say obj.proto.prop1  just use obj.prop1

*dont do this ever! for demo purposes only!!!*


```
john._proto_ = person;
```






## Everything is an object (or a primitive)

they all have protopal, expect the ```base object``` in javascript

object     have base object as proto
function    have Empty function object as proto
array       have empty array object as proto

c._proto_._proto_    what's the protopal of protopal, base object





## Reflection and extend


**Reflection**: an object can look at itself listing and changing its properties and methods.

for in   (loop over evey memver in the object)

_.extend   (check the source code of underscore)















