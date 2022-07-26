# Day 03

## Lists and Keys

### 1. What does .map() return?

---
a new array with the same length as the parent array

### 2. If I want to loop through an array and display each value in JSX, how do I do that in React?

---
you use the map() function then you return the result by {}

### 3. Each list item needs a unique ____

---
key ("string")

### 4. What is the purpose of a key?

---
they help React identify which items have been changed or added or removed so Keys should be given to the elements inside an array to give the elements a stable identity

## The Spread Operator

### 1. What is the spread operator?

---
three dots (…)

### 2. List 4 things that the spread operator can do

---

- copying an array

- combine two arrays

- adding to state in React

- combine two objects

### 3. Give an example of using the spread operator to combine two arrays

---

```
  let x = ["A", "B"];
  let y = ["C", "D"];
  let Z = [...x, ...y];
```

### 4. Give an example of using the spread operator to add a new item to an array

---
```
let numbers = [10, 9, 8];
let num = 5;
let numbers = [...numbers, num];

```

### 5. Give an example of using the spread operator to combine two objects into one

---
```
let A = {
    X: 'string 1',
    Y: 'string 2',
};


let B = {
    F: 'string 3',
    G: 'string 4'
};

let AB = {
    ...A,
    ...B
};
```

## Pass Functions Between Components

### 1. In the video, what is the first step that the developer does to pass functions between components?

---
passed state into function that he created, so he can create a setState and make it updatable.

### 2. In your own words, what does the `increment` function do?

---
it's an increasing on a value each time an event happen.

### 3. How can you pass a method from a parent component into a child component?

---
using props

### 4. How does the child component invoke a method that was passed to it from a parent component?

---
by calling it through an event
