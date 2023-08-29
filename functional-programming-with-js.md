# Functional Programming with JS

## First-class functions

- Use functiona as first class.
- Declare it using variables.

```js
const greet = function(salutation, firstName) {
  return `${salutation} ${firstName}`
}
```

## Declarative Programming

- Don't use for, while loops.
- Instead use forEach.

## Pure functions

- Returns same output for same inputs.
- Works only on its local variables.
- Doesn't change state of global variables.
```js
const add = (num1. num2) => {
  return num1 + num2;
}
```

## Immutablitiy



