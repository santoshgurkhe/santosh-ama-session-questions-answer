# AMA - 21 Sep

## 1. What is the syntax for `addEventListener()`?

`element.addEventListener("event", function);` is the basic syntax. It is used to run a function when an event happens.

## 2. What is the difference between `package.json` and `package-lock.json`?

`package.json` contains project details and dependency versions. `package-lock.json` stores the exact versions of installed dependencies.

## 3. How do you sort an object?

Objects cannot be directly sorted, so we can use `Object.entries()` and sort the resulting array based on keys or values.

## 4. How do you select an element by ID in JavaScript?

We can use `document.getElementById("id")` to select an element by its ID.

## 5. What are the events in the DOM?

DOM events are actions that happen on a webpage, like `click`, `input`, `submit`, `mouseover`, and `keydown`.

## 6. Explain the event loop.

The event loop checks the call stack and queues. When the call stack is empty, it moves the waiting tasks to the stack for execution.

## 7. What is polymorphism?

Polymorphism means one method or function can behave differently depending on the object or situation.

## 8. What are template literals in JavaScript?

Template literals are strings written using backticks `` ` ` ``. They allow us to insert variables using `${}`.

## 9. Which international organization officially standardized the DOM?

The **W3C (World Wide Web Consortium)** originally standardized the DOM. Today, DOM standards are mainly maintained through the **WHATWG** Web standards process.

## 10. What is the difference between throwing an error and returning an error?

`throw` stops the normal execution and sends the error to error handling. Returning an error just sends the error as a normal value.

## 11. What is the difference between `append()` and `appendChild()`?

`append()` can add text and multiple nodes, while `appendChild()` adds only one node at a time.

## 12. What is the difference between `setInterval()` and `clearInterval()`?

`setInterval()` runs a function repeatedly after a fixed time. `clearInterval()` stops that repeated execution.

## 13. What are the types of modules in Node.js?

The main types are **CommonJS modules** and **ES modules (ESM)**. CommonJS uses `require()` and ESM uses `import` and `export`.
