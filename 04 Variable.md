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

