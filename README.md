# Snippetstudy_Primitives_String-Method_.CharAt

## Description
This is about using the function `.CharAt`and adding characters to it.

<!---
personal note: use ctrl+f and lookup "continued" to find where you haven't finish.
-->

## Learning objectives (keywords)
* `.charAt(x)`
* `.replace(x,y)`

## Code snippet #1
```js
"a string".charAt(2) + "ee";
    // s0: (string,"a string")
    "a string".charAt (2)        
    // s1: (string, "s")
    "s" + "ee";
    // s2: (string, "see")
    "see";   
```
[repl.it]   
[pytut]   
   
S0. you begin with the starting point: you have a string and the value is "a string".  
S1. you apply a method to this string called ``.CharAt``, which takes the character at a precise index (position in the line). here the index is 2.   
>The operation is "take the character at position 2 in the string". the response state will then be a string with the value "s"      
   
S2. you want to add the string "ee" to your previour string, to make the word "see".   
   
## Code snippet #2
```js
// {number, 12345} -> {number, 345}
Number(String(12345).replace("12", ""));
  //s0  {number, 12345}
  String(12345);
  //s1  {string, "12345"}
  "12345".replace("12", "");
  //s2  {string, "345"}
  Number("345");
  //s3  {number, 345}
```
[repl.it]   
[pytut]   
   
First 2 lines summarize everything. you have the number 12345 and you want to have a number 345. 
   
 S0. you begin with the number 12345   
 S1. you apply string to it so it becomes a string with a value "12345" (you "stringarize" it?)   
 S2. you apply the method .replace to the string 1234. the values are: you are taking "12" and want to replace with "" (nothing). 
 >Now you have "345".   
    
 S3. you apply number to the string so it becomes a number (you "numberize" it?). now you have a number 345.
   
## Vocabulary
- **Object**:   
  1. _Anything that is not a primitive_: "objects are stored by reference"
  2. _The native data structure with curley braces and key-value pairs_: { key: value }
  3. __Object__ with a capital "o".  THE object built into JS, it is the top parent in any inheritance chain.
  4. "Object Oriented Programming".  A popular [programming paradigm](https://github.com/elewa-academy/programming-paradigms), source of much confusion to JS programmers:
    * _Classical OOP_: The way most programming languages do OOP.  Objects inherit their methods from Classes, and cannot (typically) be modified dynamically.
    * _Prototypical OOP_: The way JS does OOP. Objects are their own stand-alone entities, they inherit from other objects, and can be modified on the fly.   
- **Method**: JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition. Methods are functions stored as object properties.   
- **.CharAt(x)**: Method. Takes a string and returns the char at index 'x'.   
- **.replace(x,y)**: Method. Searches a string for a specified value or a regular expression (x), and returns a new string where the specified values are replaced (y).

## Review
* Struggles: 
  * fully understand the definition of a method
  * operators
* Learning objectives that need extra work?   
  value, type
  basic JS vocabulary!
  
## Helpful links
[String methods](https://www.w3schools.com/js/js_string_methods.asp)
