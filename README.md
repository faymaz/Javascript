# Javascript


```
console.log('Hello World');
alert('Alert');
```
in Webbrowser you can add JS in head or Body section.But the best practice is to put the Jscript element at the end of the body ( before the < /body> tag) section after all the existing elements. <script></script> or as a file <script src="example.js"></script>

## Comment

// This is my Comment line!
/*
 This is my Comment block!
*/

## Command Line JS code exacution

You need to download and install node https://nodejs.org the latest version.
$ node example.js 



## Variables

old versions
'var name;'

now 

'let name;' We have been declared undefined variable.

let name = 'Mosh';

// variable names can not be a reserved keyword like (let, var, if, else, true, false)
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

#### Reference Types












