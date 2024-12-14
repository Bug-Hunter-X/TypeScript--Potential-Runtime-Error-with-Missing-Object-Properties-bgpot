# TypeScript: Potential Runtime Error with Missing Object Properties

This example demonstrates a potential runtime error in TypeScript that can occur when dealing with object properties that might be missing.  While TypeScript's type system helps prevent many errors, it doesn't always catch situations where an object passed to a function lacks expected properties, leading to runtime `undefined` errors.

The `bug.ts` file contains the buggy code. The `bugSolution.ts` file demonstrates a solution using optional properties and null checks.

## How to reproduce

1. Compile the TypeScript code.
2. Run the JavaScript output.
3. The original code will throw errors if called with an object that doesn't have both 'x' and 'y' properties. The corrected version handles this gracefully.