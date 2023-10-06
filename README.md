# Javascript


```
console.log('Hello World');
alert('Alert');
alert ("Hello World!");
prompt ("How old are you?");
```

type="text/javascript" old version
<script src = "begruessung.js">
...
...
</script>

in Webbrowser you can add JS in head or Body section.But the best practice is to put the Jscript element at the end of the body ( before the < /body> tag) section after all the existing elements. <script></script> or as a file <script src="example.js"></script>

## Comment

// This is my Comment line!
/*
 This is my Comment block!
*/

html <!-- -->



## Command Line JS code exacution

You need to download and install node https://nodejs.org the latest version.
$ node example.js 



## Variables

old versions
'var name;'

now 

'let name;' We have been declared undefined variable.

let name = 'Mosh';

// variable names can not be a reserved keyword like (let, var, if, else, true, false, typeof, return)
if we use 
let if = 'Mosh'; // not valid identifier

// All ways use names meaningful (a,b,x etc)

// They can not start with numbers (5name)

// they can not contain a space or hyphen (-)

 let firstName ; // Camel notation

// Are case-sensitive

let firstName = 'Mosh', lastName = 'World'; or

let firstName = 'Mosh';
let lastName = 'World';

### Constant
const interestRate = 0.3;

### Types
#### Primitives / Value Types  (String, Number, Boolen, undefined, null)
let name = 'Mosh'; // String Literal
let age = 30; // Number Literal
let is Approved = true; // Boolean Literal false
let firstName; // undefined but we could also let firstName = undefined;
let lastName = null; // when we want to clear the value of a variable we use null

JS is a Dinamic Lanuage we can change 
let name = 'Mosh';
typeof name;
"string"
name = 1;
typeof name
"number"


contrl+L //we can clear consol

undefined is also type

#### Reference Types
Object
Array
Function



typeof
isPrototypeof


####Object
let name = 'Mosh';
let age = 30;

let person = {
 name: 'Mosh',
 age: 30
}

// Dot Notation
person.name = 'John';

// Bracket Notation
person['name'] = 'Mary';

let selection = 'name';
person[selection] = 'Mary';

console.log(person.name);

#### Array
let selectedColors = []; // Array literal indicates empty array

let selectedColors = ['red', 'blue'];
console.log(selectedColors[0]);
selectedColors[2] = 'green';
selectedColors[3] = 1;
console.log(selectedColors.length);


#### Functions declaration
function greet(){
}

greet();

function greet(name){
 console.log('Hello ' + name);
}
greet('John'); // parameter and argument
greet();


function greet(name, lastName){
 console.log('Hello ' + name + ' ' + lastName);
}
greet('John', 'Smith); // parameter and argument  // default value of variables in JS is undefined

#### Types of Functions

// Calculating a value
function square(number) {
 return number * number;
}

let number = sqaure(2);
console.log(number); // console.log(square(2));



example:
```
<html>
<body>
<h2>HTML-Change content</h2>
<p id ="section">Original text</p>
<button type = "button" onclick = "document.getElementById('section').innerHTML = 'Changed content'">Change Value</button>
</body>
</html>


// some simlpe examples

<button type = "button" onclick ="document.getElementById('section').innerHTML = 'Changed content'">Change Value</button>
<button type = "button" onclick ="document.getElementById('section').style.color ='red'">Change color</button>




<html>
<body>
<h2>Replace graphics</h2>
<button onclick="document.getElementById('myPicture').src='pic1.gif'">Pic 1</button>
<img id="myPicture" src="pic1.gif"><button onclick="document.getElementById('myPicture').src='pic2.gif'">Pic 2</button>
</body>
</html>



<html>
<body>
<h2>Access operating system features</h2>
<p id ="section">The date will appear here</p>
<button type = "button" onclick = "document.getElementById('section').innerHTML = Date()">Show date</button>
</body>
</html>

```

```
<script>
"use strict";
alert ("Hallo Welt!");
</script>
```
