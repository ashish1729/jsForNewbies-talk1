### variables

give name to a value so that its easier to use later

name should begin with letter, $ or _

*case sensitive*

**three ways to declare variables

- let
- const
- var

*we will talk about let and const only, var shall be covered later in `scopes` session maybe*

**let**
```javascript
let name = 'ashish singh'
let age = 25
let married = false

// now you can do 
console.log(name)
console.log(age)
console.log(married)

name = 'John Doe'
age = 29
married = true

console.log(name)
console.log(age)
console.log(married)
```

**const**
```javascript
const name = 'ashish singh'
const age = 25
const married = false

// now you can do 
console.log(name)
console.log(age)
console.log(married)

name = 'John Doe'
// age = 29
// married = true
```

---

**demo that values can be of different type for same variable**

---

### undefined

What happens if you create a variable, but don't assign it a value?

a special value undefined gets assigned called `undefined`

```javascript
let a;
console.log(a)
```


### no fixed types
