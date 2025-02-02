# Uncommon CSS Syntax Error: Missing Semicolon in Nested Selector

This repository demonstrates a subtle CSS syntax error that can be difficult to debug. The error occurs due to a missing semicolon after a declaration within a nested selector.

## Bug Description

A missing semicolon after a property value inside a nested CSS selector can lead to unexpected rendering behavior or parsing errors.  Browsers might interpret subsequent declarations as part of the preceding rule, causing unintended style applications or rendering issues.

## Bug Reproduction

1. Open `bug.css`
2. Observe the missing semicolon after `background-color: lightblue`
3. The missing semicolon will cause the browser to fail to correctly parse and apply the styles

## Solution

The solution is simple: add the missing semicolon to fix the syntax error.

## Solution file

The `bugSolution.css` file demonstrates the correct syntax.