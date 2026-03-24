# You want to debug a TypeScript issue in Project Nomad but are unsure about the available tools and techniques.

_Debugging TypeScript issues in Project Nomad using available tools and techniques_

## Steps

1. Use the `console.log` function to output variables and expressions to the console
2. Use a debugger like `node --inspect` or a IDE like Visual Studio Code to set breakpoints and inspect variables
3. Use the `ts-node` package to run TypeScript code directly without compiling it first
4. Use the `typescript` package to compile TypeScript code to JavaScript and inspect the output
5. Use a linter like `tslint` to identify and fix common coding errors

## Pitfalls

- ⚠️ Not using a linter to identify common coding errors, which can lead to runtime errors