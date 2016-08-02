# NativeScript + TypeScript + ES2015 demo

This is a demo project that uses TypeScript to transpile to ES2015 (using its ES6 module target in `tsconfig.json`), and then transpiling that to ES5 using Babel.

## Oh, God, but WHY?!

Use the `async`/`await` language constructs which are unavailable when transpiling TypeScript directly to ES5.
