# Uncommon TypeError in HTML: Accessing Non-Existent Element Properties

This repository demonstrates a common yet often overlooked error in HTML/JavaScript: attempting to access a non-existent property of an element.  The bug and its solution are explained below.

## Bug
The `bug.html` file contains an attempt to access a property (`nonExistentProperty`) that does not exist on the `myDiv` element. This results in a `TypeError` being thrown.

## Solution
The `bugSolution.html` file demonstrates the correct approach. Before accessing any property, it's crucial to ensure the element exists and the property is indeed defined.