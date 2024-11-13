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