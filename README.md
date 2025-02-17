# Unexpected Calculation with calc() in CSS

This repository demonstrates an uncommon bug related to the `calc()` function in CSS when used with percentage values.  In some browsers, the calculation of width using a combination of percentages and pixels within `calc()` results in an unexpected outcome, often resulting in a width of zero or an incorrect value.

The bug is demonstrated in `bug.css`. A solution addressing compatibility issues is provided in `bugSolution.css`.