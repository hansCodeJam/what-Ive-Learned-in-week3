What I've Learned in Week 4

Javascript
- A function is a subprogram designed to perform a particular task
- Parameters are variables listed as a part of the function definition.
- return - return statement stops the execution of a function and returns a value from that function.
Ex.

```Javascript
function addMc(str) {
  return "Mc" + str;
}

addMc("Donald's");
//McDonald's

function firstCharacter(str) { 
  return str[0];
}

firstCharacter('John');
//J

function capitalize(str) {
  return str.toUpperCase();
}

capitilize('usa');
//USA
```

- Booleans
  - Deals with True and False
  - && And
  - || OR

```Javascript
function alwaysTrue() {
    return true;
}

alwaysTrue(false, true, 34, 'string');
//true

function isTeacher(str){
    return str === 'teacher';
}

isTeacher('teacher');
//true
```

 - Logical Operators
```Javascript
// Logical AND operator
true  && true;  // true
true  && false; // false
false && true;  // false
false && false; // false

// Logical OR operator
true  || true;  // true
true  || false; // true
false || true;  // true
false || false; // false


function and(bool1, bool2) {
    return bool1 && bool2
}

function or(bool1, bool2) {
    return bool1 || bool2
}

and(true, true);
//true
or(true, true):
//true
```

Fahrenheit app

```Javascript
function toFahrenheit(celsius) {   
    let fahrenheit = celsius * 9 / 5 + 32; console.log(fahrenheit); 
} 

toFahrenheit(23);
//73.4
```

More, more, and more Human Rescources
