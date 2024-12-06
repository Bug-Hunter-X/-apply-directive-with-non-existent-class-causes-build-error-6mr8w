# Tailwind CSS @apply Directive Error: Non-Existent Class

This repository demonstrates a common error encountered when using Tailwind CSS's `@apply` directive: attempting to apply a class that is not defined in your configuration.  This can lead to build errors or unexpected rendering in your application.

## Reproducing the Bug

1. Clone this repository.
2. Examine the `bug.html` file. You'll see a `div` element attempting to use a non-existent class with `@apply`.
3. Build your Tailwind CSS project (the method depends on your build process).  Observe the error or unexpected result.

## Solution

The solution is simple: Ensure that the classes used with `@apply` are correctly defined in your Tailwind CSS configuration.  Verify your Tailwind configuration files (usually `tailwind.config.js` or `tailwind.config.cjs`) and ensure the classes are either included in the `content` option or defined directly within your CSS.

View the `bugSolution.html` file for a corrected example.