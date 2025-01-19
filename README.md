# Uncommon HTML Bug: Incorrect innerHTML Appending

This repository demonstrates an uncommon bug related to using `innerHTML` in HTML.  The bug occurs when attempting to append content to an element's `innerHTML` using the existing `innerHTML` value. This is inefficient and potentially creates security vulnerabilities. The `bug.html` file shows the incorrect implementation, and `bugSolution.html` demonstrates the correct approach using `insertAdjacentHTML` or DOM manipulation methods.

**Bug:** Incorrectly using `innerHTML` to modify existing content can lead to unexpected behavior.  The solution utilizes more efficient and secure methods to manipulate the DOM.

**Solution:** The preferred approach is to use `insertAdjacentHTML` or create and append elements using DOM manipulation techniques.