# Trails of compiling code 

# Front End

## Scanning/Lexing/Lexical analysis
- takes linear stream of chars and chunks them into **tokens**

## Parsing
- takes tokens and builds an **abstract syntax tree(AST)** 
- AST mirrors the nested nature of grammar 
- reports Syntax errors

## Static Analysis
### Binding/Resolution
- wire identifiers with scope
- do type check/report type error

# Middle End

## Intermediate Representations
- interface between source language and final architecture

## Optimization
### Constant folding
- evaluate a constant at compile time

## Code Generation
- generate assembly-like instructions a CPU runs

# Back End
- bytecode: virtual machine code that's not tied to any architecture

## Virtual Machine
- emulate a hypothetical chip supporting bytecode'
- slower, but simple and portable

## Runtime
- running the code in OS/virtual machine 

