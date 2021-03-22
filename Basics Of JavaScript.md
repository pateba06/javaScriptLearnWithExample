                                                         DATA TYPES

1. String Data Type: `The string data type is used to represent textual data (i.e. sequences of characters). Strings are created using single or double quotes surrounding one or more characters`

  ```js 
  var a = 'Hi there!';  // using single quotes
  var b = "Hi there!";  // using double quotes
  var a = "Let's have a cup of coffee."; // single quote inside double quotes
  var b = 'He said "Hello" and left.';  // double quotes inside single quotes
  var c = 'We\'ll never give up.';     // escaping single quote with backslash
  ```
2. Number Data Type:`The number data type is used to represent positive or negative numbers with or without decimal place, or numbers written using exponential notation e.g. 1.5e-4 (equivalent to 1.5x10-4).`
  ```js 
  var a = 25;         // integer
  var b = 80.5;       // floating-point number
  var c = 4.25e+6;    // exponential notation, same as 4.25e6 or 4250000
  var d = 4.25e-6;    // exponential notation, same as 0.00000425
  ```
3.Boolean Data Type:`The Boolean data type can hold only two values: true or false. It is typically used to store values like yes (true) or no (false), on (true) or off (false), etc.`
```js 
 var isReading = true;   // yes, I'm reading
  var isSleeping = false; // no, I'm not sleeping
  ```
  ```js 
 var a = 2, b = 5, c = 10;
 
  alert(b > a) // Output: true
  alert(b > c) // Output: false
  ```
4. Object Data Type:`The object is a complex data type that allows you to store collections of data.An object contains properties, defined as a key-value pair. A property key (name) is always a string, but the value can be any data type, like strings, numbers, booleans, or complex data types like arrays, function and other objects.`

  ```js 
      var emptyObject = {};
      var person = {"name": "Clark", "surname": "Kent", "age": "36"};

      // For better reading
      var car = {
          "modal": "BMW X3",
          "color": "white",
          "doors": 5
      }
  ```
5. Array Data Type:`An array is a type of object used for storing multiple values in single variable. Each value (also called an element) in an array has a numeric position, known as its index, and it may contain data of any data type-numbers, strings, booleans, functions, objects, and even other arrays. The array index starts from 0, so that the first array element is arr[0] not arr[1].`
  ```js 
    var colors = ["Red", "Yellow", "Green", "Orange"];
    var cities = ["London", "Paris", "New York"];
    alert(colors[0]);   // Output: Red
    alert(cities[2]);   // Output: New York
  ```
   
    
6. Null Data Type:`This is another special data type that can have only one value-the null value. A null value means that there is no value. It is not equivalent to an empty string ("") or 0, it is simply nothing.A variable can be explicitly emptied of its current contents by assigning it the null value.`
  ```js 
    var a = null;
  alert(a); // Output: null

  var b = "Hello World!"
  alert(b); // Output: Hello World!

  b = null;
  alert(b) // Output: null
  ```

7. Undefined Data Type:`The undefined data type can only have one value-the special value undefined. If a variable has been declared, but has not been assigned a value, has the value undefined.`
  ```js 
  var a;
  var b = "Hello World!"

  alert(a) // Output: undefined
  alert(b) // Output: Hello World!
  ```
                                                   
                                                   
                                                   Numbers Examples
  
  ```js 
  let number =34;
  let number1 =-1;
  let number2 =5.5;
  console.log(number);
  console.log(number1);
  console.log(number2);

  ```
  `operators` Try Below codes 1 by 1 to see how the operator performs
  
   ```js 
  let number =5.5 +2;
  console.log(number);
  ```
  
  ```js 
  let number =5.5 -2;
  console.log(number);
  ```
  
  ```js 
  let number =5.5 - -2;
  console.log(number);
  ```
  
  ```js 
  let number =5.5 * 2;
  console.log(number);
  ```

  
  ```js 
  let number =5.5 / 2;
  console.log(number);
  ```
  
  ```js 
  let number =6 % 2;
  console.log(number);
  ```
  
  ```js 
  let x =11;
  let num = x + 1 * 2;
  console.log(num);
  ```
  
  `our age represent as number, 1 dog age is 7 years to human 1 year.so we will add 1 to our age/7 for dog years`
  ```js 
  let age =26;
  let dogYears = (age + 1 )/7;
  console.log(dogYears);
  ```
  
  `Calculate percent, score 18,MaxScore 20 Percentage ?????`

  ```js 
  let studentScore =18;
  let maxScore = 20;
  let percent = studentScore / maxScore * 100;
  console.log(percent);
  ```
                           
                                            Rules For Creating Variables
  
Rule 1: You can not define variable more then once.

`Error because of re-declaring the variable. we can not define fName again`

```js
let fName='john';
let fName= 'tiger';
console.log(fName);
````

`Solution to above scenario. We are assigning new value to the existing variable we are not defining the fName again.`

```js
let fName='john';
fName= 'tiger';
console.log(fName);
````

Rule 2: There are rules related to variable names

`Variable name can not start with number. It can start with Letters or "_" or "$". Below code will show error `
```js
let 5 =4;
let result =5+5;
console.log(result);
````

Rule 3: Variable names cannot used reserved keywords

`There are many reserved keywords which we cannot used reserved keywords for naming variable. 
Below link has list of reserved keywords`
https://www.w3schools.com/js/js_reserved.asp



