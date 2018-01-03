### while loop
```javascript
let i = 0;
while(i < 10) {
  console.log(i);
  i++; // dont forget to increment
}
  
```

### do while loop
```javascript
let i = 0;
do{
  console.log(i)
} while(i > 0);
```

### for loop
```javascript
for(let i = 0 ; i< 10 ;i++ ) {
  // break syntax inside parans above
  console.log(i)
}

// for loop backwards
// for loop with different increment

```

### break
```javascript

for(let i = 0 ; i< 10 ;i++ ) {
  // break syntax inside parans above
  if( i > 5 ){
    break;
  }  
  console.log(i);
}
```

### continue
```javascript

for(let i = 0 ; i< 10 ;i++ ) {
  // break syntax inside parans above
  if( i > 5 ){
    continue;
  }  
  console.log(i);
}
```

**nested loops***
// print 11 12 13 14 21 22 23 24 31 32 33 34

### labelled statements

```javascript
/*
label:
statement
*/

outer:
for(let j = 0 ;j < 10 ; j++ ) {
  for(let i = 0 ; i< 10 ;i++ ) {
    // break syntax inside parans above
    if( i + j > 5 ){
      continue outer;
    }  
    console.log(i);
  }
}

```
