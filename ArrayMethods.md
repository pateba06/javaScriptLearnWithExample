
`Push/Pop/Shift/Unshift Methods of Array`

`PushMethod` -- It will add an object at the end of Array
```js 
var myArray = [10,20,"hello",];
myArray.unshift(11);
myArray; 
```
`Pop method` -- It will remove object from the end of Array
```js 
var myArray = [10,20,"hello",];
myArray.pop();
myArray;
```
`Unshift Method` -- It will add Object at the beginning of Array
```js 
var myArray = [10,20,"hello",];
myArray.unshift(333);
myArray;
```
`Shift Method` -- It will remove Object at the beginning of an Array.

```js 
var myArray = [10,20,"hello",];
myArray.shift();
myArray;

```

 `forEach` method of Array
 It execute function for each array elements. So if we have 3 elements it will run three times.
 ```js 
var myArray = [ 10,20,"Hello"];
var myFunction = function(){
  console.log("For an element")
}
myArray.forEach(myFunction);
```

```js 
var myArray = [ 10,20,"Hello"];
var myFunction = function(item){
  console.log("For an element" + item)
}
myArray.forEach(myFunction);
```

