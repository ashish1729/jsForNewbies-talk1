## functions

block of code which you might want to call more than once

*a set of statements that performs a task or calculates a value*

### syntax 

```javascript
//defining function
function hello() {
  console.log('hello world');
}

//calling function
hello();
```
###### output:
```
hello world
```


***taking parameters***
```javascript
function hello(name) {
  console.log('hello ' + name);
}

// parameters can be more than one
// addition example
function helloToMany(name1, name2) {
  console.log('hello ' + name1 + " and " + name2);
}

hello("ashish");
helloToMany("ashish", "janardan");

```
###### output:
```
hello ashish
hello ashish and janardan
```


***return statement***

```javascript
// function can give a value which we can use
// we use return statement to make a function give us a value
function add(a,b){
  let ans = a + b;
  return ans;
}
let result = add(10,20);
console.log(result);
```
###### output
```
30
```

### function declaration
**above syntax***

```javascript
function test(args) {
  //body
}
```


### function expression

```javascript
const myFunction = function () {
  //body
}
```


### arrow functions 

*are for function expressions*

[mdn link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
