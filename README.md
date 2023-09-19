# Lesson 1.2: Variables & Conditionals

Welcome to the lesson on IDEs, Variables, and Conditionals! This README serves as a reference tool to review key points and includes code snippets to help reinforce learning.

## Table of Contents:
- [CodeSandbox Introduction](#codesandbox-introduction)
- [Variables in JavaScript](#variables-in-javascript)
- [Technical Questions](#technical-questions)
- [JavaScript Math](#javascript-math)
- [Conditionals in JavaScript](#conditionals-in-javascript)


---

### CodeSandbox Introduction

#### What is CodeSandbox?
- Online editor tailored for rapid web development.
- Quickly prototype, experiment, share, and debug your code.
- Supports multi-page websites and various frameworks or libraries.
- Collaborative coding enabled through live sharing.

#### Quick Start:
1. **Login**: Go to [CodeSandbox](https://codesandbox.io/) -> Sign In using GitHub.
2. **Creating a Sandbox**:
    - Click `Create` -> Choose `Vanilla` from Official Templates.
    - Your new sandbox will load up with an `index.html` file ready to edit.
3. **Navigating**: The left navigation panel provides access to various features such as:
    - Sandbox Info, Explorer, Search, Configuration Files, GitHub Integration, Deployment options, and Live collaboration.

**Note**: For detailed exploration of CodeSandbox, follow the teacher's guide provided in the lesson.

---

### Variables in JavaScript

Variables are containers that store data values.

#### Declaring a Variable:
```javascript
let box;
```

#### Assigning a Value to a Variable:
```javascript
box = 10;
// or
let box = 10;
```

#### Re-assigning Value:
```javascript
box = 15;  // Now, box has a value of 15
```

**Note**: Variable names should be descriptive, can't start with a number, and can't use JS keywords.

---

### Technical Questions

- Contextualize your question: explain what you're trying to achieve.
- Specify the problem and indicate any solutions you've already tried.
- Sharing your code can often help in resolving the issue faster.

**Example**: Instead of saying "My code doesn't work", you might say:
"I'm trying to fetch user data from an API using JavaScript, but I'm getting a 404 error. I've checked the endpoint URL, and it seems correct. Can someone take a look at my fetch function?"

---

### JavaScript Math

Basic arithmetic works intuitively:

```javascript
5 + 2  // 7
5 * 2  // 10
5 - 2  // 3
5 / 2  // 2.5
```

**Example with Variables**:
```javascript
let myNumber = 12;
myNumber / 3  // 4
```

---

### Conditionals in JavaScript

Conditionals allow you to execute different code branches based on conditions.

**Basic `if` Statement**:
```javascript
if (myNum === 8) {
    console.log("8 is great!");
}
```

**`if-else` Statement**:
```javascript
if (myNum === 8) {
    console.log("8 is great!");
} else {
    console.log("That number is OK.");
}
```

**`if-else if-else` Statement**:
```javascript
if (myNum === 8) {
    console.log("8 is great!");
} else if (myNum < 10) {
    console.log("Wow. Less than 10?");
} else {
    console.log("That number is OK.");
}
```


Happy coding!
