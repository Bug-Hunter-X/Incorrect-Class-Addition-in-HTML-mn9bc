# Incorrect Class Addition in HTML

This repository demonstrates a common mistake when working with HTML classes.  The example shows an attempt to add a class directly to an element using the incorrect syntax `element.class = "className"`, which results in the class not being applied. The solution shows the correct method using `element.classList.add("className")`.

## Bug

The `bug.html` file demonstrates the incorrect approach. Observe that the text within the div is still visible, even though the `hidden` class is intended to hide it. This is because the attempt to add a class directly to the `class` property failed.

## Solution

The `bugSolution.html` file showcases the correct way to add a class to an HTML element using `classList.add()`.  This approach appropriately modifies the element's class list, allowing you to add or remove classes with more flexibility.