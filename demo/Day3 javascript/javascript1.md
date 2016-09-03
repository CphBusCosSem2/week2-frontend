#Javascript
##Introduction

-	Lets start by doing som js
--Set up external js document to alert()
--React to a div being clicked
--console.log() vs alert()
--Internal vs external js script

##Content
-	What is js (Scripted, Syntax…)
-	Loosely typed
-	Variables
-	Data types
-	Operators
-	Functions (methods in objects)
-	Objects
-	Array and array methods

##Oddities
https://www.smashingmagazine.com/2011/05/10-oddities-and-secrets-about-javascript/

-	Null is an object
-	NaN is a Number
-	NaN er ikke NaN
-	Empty array is false
	(more or less..)

##Loosely typed
-	Examples

##Values
-	numbers, (max 64bit)
--Integer and floating points (NaN, infinity, -infinity)
-	strings, 
-- (+, \n, “typeof” operator that returns a string)
-	Booleans, 
--Operators (unary, binary and ternary)
-	Objects, 
-	Functions, 
-	Undefined values (null and ‘undefined’)
##Truthy vs. Falsy
-	Every non-boolean value has a built-in boolean flag
-	[ ] == false;
-	null == false;
-	“” == false;
-	0 == false;

##Operators
-	Unary operators: (typeof and instanceof)
-	Binary operators:
--String Operators
--Arithmetic Operators (+, -, *, /, %...)
--Assignment Operators (=, +=, -=, *=, ….)
--Logical Operators (==, ===, !==, <, >=, …)
-	Ternary operators:

##Functions
-	Functions vs. Methods (in objects).
-	Declaration:
-	Hoisting: 
-	Only when declared as a function.
-	IIFE (immediately Invoked Function Expression)

##Function arguments
-	Extra arguments are ignored
-	Too few arguments and the value will be set to ”undefined”
-	The arguements 
    property:
Self invoked funtions
Var myfunc = function(){
Some functionality….;
}();
##Scope
-	Scope is the set of variables you have access to.
--Global scope (Default)
--Function scope
--Nested scope
##The ‘this’ keyword
-	‘this’ refers to the owner of the function we are executing. (The object that the function is a method of)
-	If ‘this’ is used in a function that is not a method it will refer to the global object (the window object of the browser).
##Closures
-	For encapsulation
##Callback functions
-	High-order functions (functions as arguments)
-	To be called at a later point
-	Examples:
##Callbacks continued
-	Callbacks are closures (can access the containing functions scope)


##Objects
-	Var myObject = { };
-	Can contain properties and methods.
-	Constructor
##Arrays
-	[ ]
-	Properties:

-	Methods:
##Exceptions and errors
-	Exceptions tutorial
##map
Filter and map
-	Example of dot notation
