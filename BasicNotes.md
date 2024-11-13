# JavaScript:
&nbsp; JavaScript is a general purpose Just In Time Compilation language which is used to create a dynamic webpages. JavaScript can be run in JavaScript Engine which is present in the browser. JavaScript is single threaded and JavaScript can perform asynchronous operations, like handling API requests or timers, through functions like setTimeout, fetch, and Promises.. It supports all procedural, functional and Object Oriented Programming. With the versatality of JavaScript we can use react library with association of other libraries to create a framework and with node js we can perform backend work. It is totally different from HTML and CSS because javascript is a general purpose language but html and css are not. We can't write any logic using HTML and CSS. With that we can create static webpage. 

# Variables:
&nbsp; In javascript variables can be defined as a container which will store the value or the memory address of the value location. According to the data type i.e., for primitive datatype like (number, string, undefined, null, boolean) are stored as value. The non primitive datatype like arrays, function, object are stored its memory address. To declare a variable in normal mode it is recommended to use let, var, const keyword. In strict mode with out declaring we can't use the variable. let is a keyword which give access to the data declared in it in local level. let variable can be declared once and initialize and reinitialize when ever we want. var is the keyword which give scope to the data in functional level. var can also be declared once and initialize or reinitialize when ever we want. const is also keyword which is used to declare the variable that cannot be reinitialize or changed. 

# Data Type:
&nbsp; Data type can be defined as the kind of data which allows as to store and manipulate in the memory location. By the help of data type we can perform some certain specific operation on it which improves the program and efficiency. In javascript they are two types of data type. They are:
1. Primitive datatype
2. Non-Primitive datatype

## Primitive Datatype:
&nbsp; Primitive datatype are the datatype which will be stored in the memory as value. These values are stored in stack memory. They are seven type of Primitive datatype. They are:
* number
* string
* boolean
* null
* undefined
* BigInt
* symbols

### Number:
&nbsp; Number are the datatype which consists of integer and float. Unlike than other programming language here the float and number are treated as same data type. For Example
```js
let num1 = 25;
let num2 = 25.5;
```

### String:
&nbsp; String are the datatype which accepts all alphabet, numbers and special character within single, double and backtick cotation. It is homogeneous in nature. For Example:
```js
let str1 = "Hii";
```

### Boolean:
&nbsp; Boolean is a datatype which consists of true or false value. For Example:
```js
let bool = true;
```

### null:
&nbsp; Null is a falsy value which will be represent when there is no object in the variable. For Example:
```js
let obj = null;
```

### undefined:
&nbsp; Undefined is a falsy value which will be present when we are declared and initialized it.For Example:
```js
var word;
```

### BigInt:
&nbsp; Bigint is a number kind of datatype which is used to store large number that cannot be handled by number. For Example:
```js
let bigNumber = 123456789632599655566325;
```

### Symbol:
&nbsp; The symbol is a immutable datatype which is used in object property keys. For Example:
```js
let obj = Symbol("something");
```

## Non Primitive Datatype:
&nbsp; The non primitive datatpe is a datatype which stores the address or reference of the value in the variable. They are no specific types. All user defined arrays, inbuild function, function and objects are non primitive datatype.
```js
let a = [1, 2];
let b = {"a" : 1}
let c = (ele)=>ele * 2;
```

# Input Method:
&nbsp; In javascript we can take inputs from user in so many ways. The first method is `prompt`. The prompt is used to take input from user in console directly. It takes the non mandatory arguments which is string that will be display during the code is loaded. The second way is through input field HTML tag. The user can give input through for form input field. By using DOM concept we can fetch the data from the field directly. By using the `value` attribute we can import the text written by user. By using `addEventListner` we can get the value by some action like `submit` or `input`. These are the ways to get the user input value. 

# Operators:
## Difference between `==` and `===`:
|S.No|`==`|`===`|
|----|----|-----|
|**1.**|`==` is a relational operator which takes two operands|`===` is a relational operator which also takes two operands|
|**2.**|`==` will compares the value not its data type|`===` will compares the value as well as data type.|
|**3.**|In `==` type coversion will occur implicitily|In `===` the type coversion will not occur.|
|**4.**|For example` 5 == '5'` will return `true`.|For example `5 === '5'` will return `false`.|

## Difference Between `&` and `&&`:
|**S.No**|**`&`**|**`&&`**|
|--------|-------|--------|
|**1.**|**`&`** is a bitwise operator|**`&&`** is a logical operator|
|**2.**|**`&`** takes two operands as number|**`&&`** will takes two operands as boolean value.|
|**3.**|**`&`** return a number datatype.|**`&&`** return a boolean datatype|
|**4.**|It converts the given number into binary number and compares two numbers if both are one it return one if anyone is zero it returns zero after collecting all binary numbers it convert it into number and display to us|It takes two boolean value. If two boolean value is true it returns true if anyone is false it returns false.|

# Function:
&nbsp; The function can be defined as the block of statement which used to some specific task when ever it is called. The function are first class citizen because these function can be stored in a variable, function can be passed or taken as arguments to another function. The function can be classified into three types. They are:
1. Function declaration
2. Function Expression
3. Arrow Function

## Function Declaration:
&nbsp; The function declaration is a way to declare a function using the function keyword which will be followed by a identifier and paranthesis where we can pass arguments. The block of code is written inside the braces. If we print the function address we get actual function as output. These function can be called before its declaration. For Example:
```js
main();
function main(){
    console.log("Hello World");
}

