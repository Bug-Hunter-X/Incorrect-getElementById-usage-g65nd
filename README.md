# Uncommon HTML Bug: Incorrect getElementById Usage

This repository demonstrates a subtle bug in HTML/JavaScript related to accessing DOM elements by ID. The bug arises from a simple typo in the `getElementById` function call.

## Bug Description
The provided HTML code attempts to change the innerHTML of a div element with id 'myDiv'.  However, instead of correctly using `document.getElementById`, it uses `document.getElementByIdx`, causing a runtime error and preventing the intended modification.

## Solution
The solution involves correcting the typo in the JavaScript code, using the correct `document.getElementById` method to access the element and modify its content.

## How to reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the error in your browser's console.
4. Open `bugSolution.html` to see the corrected code and the intended behavior.