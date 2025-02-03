# TypeScript Type Error in Function Arguments

This repository demonstrates a common type error in TypeScript where a function receives arguments of incorrect types.

## Bug

The `add` function is defined to accept two numbers as arguments. However, in the call to `add`, the second argument is a string. TypeScript correctly flags this as a type error. The `bug.ts` file demonstrates the incorrect function call.

## Solution

The solution involves ensuring that the arguments passed to the `add` function are both numbers. The `bugSolution.ts` file provides a corrected version where type checking is handled, preventing the type mismatch. This illustrates proper type handling in TypeScript to prevent runtime errors. 