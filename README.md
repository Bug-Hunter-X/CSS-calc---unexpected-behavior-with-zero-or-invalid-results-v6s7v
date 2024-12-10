# CSS calc() Unexpected Behavior

This repository demonstrates an uncommon issue with the CSS `calc()` function.  Some browsers handle calculations resulting in zero or invalid values (like division by zero) inconsistently.

The `bug.css` file shows the problematic code, while `bugSolution.css` provides a solution.

## Bug
Calculations that resolve to 0 or are mathematically invalid may cause rendering errors or unexpected behavior in certain browsers.  This is not a widely documented problem.

## Solution
The solution usually involves avoiding calculations that could produce these problematic results.  Alternative approaches could include conditional CSS or JavaScript to dynamically handle the styling.