%ES7 Typed Objects
%CSCI 3155
%**J**esus Ortiz, **A**licia Frisone, **B**rooke Robinson, **S**laton Spangler


Introduction of Typed Objects
====
* A feature of ECMAScript 7 
* Allows the use of defined types in objects
* Proposed to better the memory storage of objects
* More predictable performance
   

***
History
====
* JavaScript is a dynamically typed language
* Assigning different types to the same variable allowed
* ES^ introduced typed arrays, but they have their limitations


***
Typed Arrays and Typed Objects
====
* Typed Objects are generalizations of Typed Arrays
* Typed Arrays cannot use non scaler types
..* References to objects
..* Structs
* Typed objects overcome these limitations


***
What types are supported?
====
--- | --- | ---
any | uint8 | int8
float32 | object | uint16
int16 | float64 | string
uint32 | int32 | 

***

Overview of Presentation
====
* Motivation
* The difference with semantics and syntax
* Comparison to Typed Arrays
* About Typed Objects
* Implemenation
* Examples
* Pros
* Cons
* Performance
* Summary/Conclusion/References


***

Example
====

````javascript
def f(x):
	return x * 2
````
