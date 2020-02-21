1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
//name is the name of memory location where string "mark" is stored. 
```

2. Find the error if any
```js
  var product cost = 3.45;
```
```js
// This is not the right way to declare a variable 
  var productcost = 3.45;
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" - Right
  'Hello World" - Wrong
  "Hello World' - Wrong
  'Hello World' - Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; - VALID
var 1girl; - INVALID
var woman3; - VALID 
var -girl; - INVALID
var blackDog; - VALID
var 42; - INVALID
var $42; - VALID 
var userName; - VALID
var x, y, z; - VALID
var x = 5, y = 6, z = 7; - VALID
var x = 5 + 10 + 2; - VALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
```
// Define a new variable and store the value that is 80 less then the value of amount.
```js
var a = amount - 80; 
console.log(a);
```
// Define a new variable and store the value that is 200 more then the value of amount.
```js
var a = amount + 200;
console.log(a);
```

// Define a new variable and store the value that is 4 times the value of amount.
```js
var a = amount * 4;
console.log(a);
```

// Define a new variable and store the reminder when the value of amount is  divided by 21.
```js
var a = amount % 21;
console.log(a);
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark
// Check who is younger
if (johnAge > markAge) {
  console.log("John is Older than Mark")
}
else {
  console.log("Mark is Older than John")
}

// Check if their age is equal
if (johnAge == markAge) {
  console.log("Age is equal")
}
else {
  console.log("Age of both are not equal")
}

// Create a new variable and assign the age of john to new variable.
var johnAge = 45;
var a = johnAge;
console.log(a)

// Check if john is equal to or greater then mark.
if (johnAge >= markAge) {
  console.log("John is equal to or greater then mark.");
}
else {
  console.log("john is not equal to or not greater then mark");
}

// Check if john is less then or equal to mark.
if (johnAge <= markAge) {
  console.log("John is equal to or greater then mark.");
}
else {
  console.log("john is not equal to or not greater then mark");
}

// Calculate the average age of john and mark and assign to a new variable.
var avgAge = (johnAge + markAge)/2
console.log(avgAge)
```