# Day 05

## Thinking in React

### 1. What is the `single responsibility principle` and how does it apply to components?

---
every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

### 2. What does it mean to build a ‘static’ version of your application?

---
a compiled version of a program which has been statically linked against libraries.

### 3. Once you have a static application, what do you need to add?

---
build components that reuse other components and pass data using props only and we don't use state since it static.

### 4.What are the three questions you can ask to determine if something is state?

---

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

### 5.How can you identify where state needs to live?

---
if our component depends on a data to render and show some results, then this data can be placed in state. State changes, component rerenders and show results depending on the state.

## Order Functions

### 1. What is a “higher-order function”?

---
Higher Orders Functions are functions that perform operations on other functions.

### 2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?

---

```
function greaterThan(n) {
return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
//true
```

returning a logic to comparing m and n which returns boolean.

### 3. Explain how either `map` or `reduce` operates, with regards to higher-order functions.

---

`reduce` will return single value.
`map` will return the whole array.
