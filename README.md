# Unexpected Behavior with CSS `calc()` Function

This repository demonstrates an uncommon issue that can arise when using the CSS `calc()` function.  The problem involves unexpected results from `calc()` due to inconsistencies in units or missing spaces in the calculation.  The example shows how seemingly small mistakes can lead to rendering problems.

## Bug Description
The `calc()` function, while powerful, is prone to errors if not used carefully.  Inconsistent units or omitting spaces between operators and operands can lead to unexpected behavior and incorrect rendering of elements.

## How to Reproduce
1. Open `bug.css`
2. Observe the unexpected width of the `.element` element.  The calculation is incorrect due to a missing space.
3. Open `bugSolution.css` to see the correct implementation.