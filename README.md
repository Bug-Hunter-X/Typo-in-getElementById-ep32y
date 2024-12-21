# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a simple yet easily overlooked bug in HTML/JavaScript. The bug stems from a common typo in the `getElementById` method, leading to unexpected behavior. 

## Bug Description

The `bug.html` file contains a typo in the JavaScript code. Instead of using the correct method `getElementById`, it uses `getElementByIdx`, which does not exist and leads to no changes in the HTML element.

## Solution

The `bugSolution.html` file demonstrates the correct way to change the content of a div element using `getElementById`.