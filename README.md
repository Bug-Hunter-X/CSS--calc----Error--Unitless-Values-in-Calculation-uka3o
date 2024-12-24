# CSS `calc()` Error: Unitless Values

This repository demonstrates a common yet subtle error in CSS that can occur when using the `calc()` function.

The problem arises when unitless numbers are used directly within `calc()` expressions. The `calc()` function expects its operands to be properly unit-specified. This example shows the error and its solution.

## The Problem

The `bug.css` file contains CSS code that attempts to calculate a width using `calc()`, but it uses a unitless number causing an error or unexpected results across different browsers.

## The Solution

The `bugSolution.css` file shows the correct way to use the `calc()` function, ensuring the proper inclusion of units with each numeric value in calculations.