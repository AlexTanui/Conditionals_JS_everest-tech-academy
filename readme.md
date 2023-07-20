
---

**Conditionals in JavaScript**

Conditionals are used in JavaScript to make decisions in code based on specific conditions. They allow you to execute different blocks of code depending on whether a particular condition is true or false. Below are the different types of conditionals in JavaScript:

1. **if statement:**

The `if` statement is used to execute a block of code if a specified condition evaluates to true.

```javascript
const age = 25;

if (age >= 18) {
  console.log("You are an adult.");
}
```

2. **if...else statement:**

The `if...else` statement allows you to execute one block of code if the condition is true and another block if the condition is false.

```javascript
const time = 13;

if (time < 12) {
  console.log("Good morning!");
} else {
  console.log("Good afternoon!");
}
```

3. **if...else if...else statement:**

The `if...else if...else` statement allows you to check multiple conditions and execute different blocks of code accordingly.

```javascript
const score = 75;

if (score >= 90) {
  console.log("Excellent!");
} else if (score >= 70) {
  console.log("Good job!");
} else {
  console.log("Keep trying!");
}
```

4. **Ternary Operator:**

The ternary operator is a shorthand way to write simple if...else statements in a single line.

```javascript
const age = 20;

const result = age >= 18 ? "Adult" : "Minor";
console.log(result); // Output: Adult
```

5. **switch statement:**

The `switch` statement is used to compare a value against multiple cases and execute the corresponding code block.

```javascript
const day = "Monday";

switch (day) {
  case "Monday":
    console.log("Start of the week");
    break;
  case "Tuesday":
    console.log("Second day");
    break;
  default:
    console.log("Some other day");
}
```

In JavaScript, conditionals are an essential part of the language. They allow you to control the flow of your code based on various conditions, making your programs more dynamic and flexible.

---

