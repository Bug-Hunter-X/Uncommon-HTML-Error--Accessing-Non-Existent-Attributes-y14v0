# Uncommon HTML Error: Accessing Non-Existent Attributes

This repository demonstrates an uncommon error in HTML related to accessing non-existent attributes on HTML elements.  The error is subtle and might not immediately throw an exception but could lead to unexpected behavior in the application.

## Description

The `bug.html` file contains a simple HTML page that tries to access a non-existent attribute on a div element. This usually results in `undefined` but doesn't always cause a clear error that is easy to debug.

## Solution

The `bugSolution.html` file demonstrates the proper way to check for the existence of attributes before accessing them.  Using a more robust approach reduces the risk of runtime errors or unexpected behavior.