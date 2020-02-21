# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true; //output true
true  && false; //output false
false && true; //output false
false && false; //output false
"foo" && "bar"; //output bar
"bar" && "foo"; //output foo 
"foo" && ""; //output "" 
""    && "foo"; //output "" 
" "   && "John" && "" && false //output ""   
false && "Hey" && undefined //output false
"undefined" && false && 42 //output false
```

* [ ] Logical OR operation
```js
true  || true; // output true
true  || false; // output true
false || true; // output true
false || false; // output false
"foo" || "bar"; // output "foo"
"bar" || "foo"; // output "bar"
"foo" || ""; // output "foo"
""    || "foo"; // output ""
" "   || "John" || "" || false // output " "
false || "Hey" || undefined // output "Hey"
"undefined" || false || 42 // output "undefined"
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"
```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
// Your code goes here
if ((isGuestOneVeg==true) && (isGuestTwoVeg=true))
{
    alert("Only offer up veg dishes")
}
else if ((isGuestOneVeg==false)&&(isGuestTwoVeg==false))
{
    alert("Offer up anything");
}
else if (((isGuestOneVeg==true) && (isGuestTwoVeg=false)) || ((isGuestOneVeg==false) && (isGuestTwoVeg=true)))
{
    alert("offer up some veg options ")
}
else {
    alert("Error");
}
```


3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
// Your code goes here
if (temperature < 32) {
    alert("It is freezing outside")
}
else if (temperature > 110) {
    alert("It is hot outside")
}
else {
    alert("Go for it. It is pretty nice out");
}
```


4. 🎖 Output of this and the reason behind the output.
```js
alert( alert(1) || 2 || alert(3) );
```
// Output - alert(1) and 2
// The second value within the main alert( ) 2 is truthy value so it stops there.
// Before showing 2 it has already checked for alert(1) and shown the 1 in alert window.
