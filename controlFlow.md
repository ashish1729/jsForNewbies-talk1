### if 

**condition can be anything**
*but try that it is mostly boolean*

```javascript
if(true) {
  console.log('true');
}

if(false) {
  console.log('false');
  }
```

### if else

```javascript
if(true) {
  console.log('true');
} else {
  console.log('false');
}

if(false) {
  console.log('true');
} else {
  console.log('false');
}
```
### truthy and falsy values

**falsy values**
- if (false)
- if (null)
- if (undefined)
- if (0)
- if (NaN)
- if ('')
- if ("")

**comparison operators review, they return boolean**

### logical operators

- and ( && )
- or ( || )
- not ( ! )

### else if

``` javascript
let a = 12

if(a < 10) {
  console.log('less than 10');
} else if(a < 20) {
  // note that we dont check for 10 again
  console.log('between 10 and 20');
} else {
  console.log('greater than 20');
}

```
### switch statements

```javascript
let num = 2
switch(num) {
  case 1:
    console.log(1);
  case 2:
    console.log(2);
  default:
    console.log('not one or two!!!');
}
```

```javascript
let num = 2
switch(num) {
  case 1:
    console.log(1);
    break;
  case 2:
    console.log(2);
    break;
  default:
    console.log('not one or two!!!');
}
```

### ternary operator

```javascript
true ? console.log('is true') : console.log('is false');
false ? console.log('is true') : console.log('is false');

// some examples with operator above
```
