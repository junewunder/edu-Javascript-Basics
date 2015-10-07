# Javascript Basics

For fancy documentation with basically the same information, go to: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures

### Table of Contents  
|||
|:- | :--------- |
| 1 | Primitives |
| 2 | Arrays     |
| 3 | Objects    |
| 4 | Functions  |
| 5 | Classes    |

## Primitives

Primitives are the most basic data types.  They cover any type of data one could want to store.

### Boolean

A boolean is a variable that's either `true` or `false`

```javascript
var yes = true;
var no = false;
```

### Null

Null is a value to represent nothing.  When a variable is set to null it has the value "null".
```javascript
var nothing = null;
console.log(nothing); // null
```

### Undefined

Undefined is when a variable doesn't have a value. Variables are set to be undefined when they're not given a value at creation.

```javascript
var whatsThis;
console.log(whatsThis); // undefined
```

Variables can be set to the value `undefined`.
```javascript
var stillNoValue = undefined;
console.log(stillNoValue); // undefined
```
But there's no reason to do that, so don't...

### Number

Numbers are the data type for any number.  Javascript doesn't distinguish between integers and numbers with decimals (floats).

```javascript
// these are the same type to javascript
var number = 1;
var another = 1.337;
```

Numbers can be added `+`, subtracted `-`, multiplied `*`, and divided `/`

### String

Strings hold text. They're used to hold data that isn't a number. Strings are denoted using a single or double quote `''` `""`. Strings can also be denoted with back ticks
` `` `

```javascript
var string = "the cat in the hat";
```

Strings can be "indexed" by using square braces after the variable name. Indexing a string returns the value at that position in the string.

WARNING: Indexing starts counting at 0

```javascript
var string = "the cat in the hat";
console.log(string[0]); // t
console.log(string[5]); // a
```

The operators `+` and `+=` can also be used for strings.

## Arrays
Arrays are used to hold more than one value.

## Objects

## Functions

## Classes
