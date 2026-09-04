# Compilers

Interactive and implementation-first resources for understanding how source code becomes tokens, syntax trees, intermediate representations, machine code, or executable behavior.

## Resources

| Resource | Description |
|---|---|
| [AST Explorer](https://ast-explorer.dev/) | Paste code and instantly inspect its abstract syntax tree using many different parsers. Great for developing intuition for syntax trees and transformations. |
| [Compiler Explorer](https://godbolt.org/) | Edit source code and immediately see the assembly or compiler output produced by GCC, Clang, MSVC, Rust, and many other toolchains. |
| [LLVM - My First Language Frontend](https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/) | Build a small programming language step by step using LLVM, from lexer and parser through AST, LLVM IR, JIT compilation, and object-code generation. |

## The compilation pipeline

`Source` → `Lexing` → `Parsing` → `AST` → `Semantic analysis` → `IR` → `Optimization` → `Code generation`

## Core concepts to understand

- lexers and tokens
- grammars and parsing
- recursive descent
- abstract syntax trees
- symbol tables and scopes
- type checking
- intermediate representations
- control-flow graphs
- SSA
- compiler optimizations
- code generation
- register allocation
- linking and loading
- interpreters vs. compilers vs. JITs

## Best way to learn

Write a tiny language. Even one with variables, arithmetic, `if`, functions, and a basic type system will make compiler architecture much less abstract.

[← Back to main README](../README.md)
