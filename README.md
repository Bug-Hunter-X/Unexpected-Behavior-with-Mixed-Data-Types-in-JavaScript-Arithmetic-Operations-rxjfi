# JavaScript Bug: Unexpected Arithmetic Behavior with Mixed Data Types

This repository demonstrates a common JavaScript bug related to loose typing and arithmetic operations. The bug arises when performing arithmetic operations with mixed data types (numbers and strings), leading to unexpected results due to JavaScript's automatic type coercion. 

## Bug Description

The core issue is the implicit type coercion performed by JavaScript when mixing number and string types in an arithmetic context.  Instead of raising an error, JavaScript attempts to convert the string to a number, which might not always work as expected. This typically leads to unexpected outputs or runtime errors (NaN).

## Bug Reproduction

1. Clone this repository.
2. Open `bug.js`.
3. Run the code using a JavaScript interpreter (Node.js, browser's console, etc.).
4. Observe the unexpected output when a string is passed to the `bar` function.

## Solution

The solution involves explicit type checking and conversion to ensure that both inputs are of the correct type before performing arithmetic.  The solution is available in `bugSolution.js`.

## Contribution

Feel free to contribute to this repository by improving the bug description, adding more examples, or suggesting better solutions.