# CSS Calc() Function Syntax Error

This repository demonstrates a common yet easily overlooked error when using the `calc()` function in CSS. The error occurs due to a missing space between the percentage value and the arithmetic operator within the `calc()` expression. This can result in unexpected layout or rendering issues.

## Bug Description
The provided CSS code attempts to calculate the width of a `div` element by subtracting 10 pixels from 100% of the container's width. However, the missing space between `100%` and the `-` operator causes a parsing error, potentially leading to the element not rendering as expected.

## How to Reproduce
1. Copy the code from `bug.css` into your CSS file.
2. Apply this style to a `div` element in your HTML.
3. Observe the unexpected behavior; the width of the `div` will not be correctly calculated.

## Solution
The solution is simple: ensure that there are spaces around the arithmetic operators within the `calc()` expression.