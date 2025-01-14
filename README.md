# CSS `calc()` Function Bug

This repository contains a bug report and solution for a problem encountered with the CSS `calc()` function when used with percentage values and other units.  The bug involves incorrect calculation when combining percentages with fixed units like pixels.

## Bug Description

The `calc()` function, while powerful, doesn't always behave as expected. When combining percentages with fixed units (like `px`, `em`, etc.), the calculation may not resolve correctly. This can lead to unexpected layout issues.

## Solution

A workaround is to utilize multiple CSS rules and avoid combining percentages and other units in a single `calc()` expression. By breaking down the calculation, you can achieve the desired layout behavior.

## Usage

Refer to the `bug.css` and `bugSolution.css` files for code examples illustrating the problem and the solution.