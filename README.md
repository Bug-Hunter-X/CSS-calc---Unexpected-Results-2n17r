# CSS calc() Unexpected Behavior

This repository demonstrates an uncommon bug related to the CSS `calc()` function. The bug occurs when `calc()` produces a negative value or when units are inconsistently used within the calculation.

## Bug Description
The CSS `calc()` function can lead to unexpected results if the calculation produces a negative value (e.g., subtracting a larger value from a smaller value) or if units are inconsistent within the calculation.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`.
3. Observe how the `width` of the element is rendered differently in each file, illustrating the incorrect behavior in `bug.css` and the correct solution in `bugSolution.css`.

## Solution
The solution involves careful consideration of the calculation being performed to avoid negative values.  Units should also be made consistent within the expression.