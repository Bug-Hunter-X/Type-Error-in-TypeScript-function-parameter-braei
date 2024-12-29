# Type Error in TypeScript Function Parameter

This example demonstrates a common type error in TypeScript that occurs when passing an argument of an incorrect type to a function.

## Bug

The function `greeter` expects a single string as input.  However, the code attempts to pass an array of strings to the function.  TypeScript correctly identifies this as a type error.

## Solution

The solution involves ensuring the correct type is passed to the function.  This can be achieved by accessing the individual elements of the array, or by modifying the function signature to accept an array.