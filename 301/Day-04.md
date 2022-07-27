# Day 04

## Lists and Keys

### 1. What is a ‘Controlled Component’?

---
its a component which renders form elements and controls them form the component's state by keeping them.

### 2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

---
we have to update it immediately when they been submitted, to avoid problems and errors with rendering.

### 3. How do we target what the user is entering if we have an event handler on an input field?

---
this.setState({value: event.target.value} 

## The Spread Operator

### 1. Why would we use a ternary operator?

---
as a solution for the long if and else statements and make it shorter

### 2. Rewrite the following statement using a ternary statement:

```

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

```

---

`x===y ? console.log(true) : console.log(false)`
