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


***taking parameters
```javascript
function hello(name) {
  console.log('hello ' + name);
}

// parameters can be more than one
// addition example
```

***return statement

```javascript
// function can give a value which we can use
// we use return statement to make a function give us a value
function add(a,b){
  let ans = a + b;
  return ans;
}
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
function () {
  //body
}
```


### arrow functions 

[mdn link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
