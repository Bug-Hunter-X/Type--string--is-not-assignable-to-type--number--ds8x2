# Type 'string' is not assignable to type 'number' in TypeScript

This repository demonstrates a common type error in TypeScript where a string is passed to a function expecting a number.  The error message is clear: `Type 'string' is not assignable to type 'number'.`

The `bug.ts` file showcases the erroneous code. The `bugSolution.ts` file provides a corrected version.

This error is frequently caused by:

* **Incorrect Data Types:**  Variables or function arguments are of the wrong type.
* **Implicit Type Conversions:** TypeScript's type system is strong but it doesn't automatically convert between strings and numbers.
* **Data from External Sources:**  If your data comes from a source that doesn't guarantee the correct type (e.g., user input, an API), robust type checking and validation are crucial.