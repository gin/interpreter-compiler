# Interpreter and Compiler

I looked at EVM, OVM, CosmWasm and Gnolang, and wanted to know how those work. I figured it would be a good idea to go through some books on interpreters and compilers. I chose to write an interpreter and a compiler in Go because I am more familiar with Go than C++. Maybe I'll try out C++ in the future.  

## Interpreter
Tree-walking interpreter.  
1. Parse source code
    * lexer
    * parser
2. Build an abstract syntax tree (AST)
    * AST
    * internal object system
3. Evaluate the AST
    * evaluator

## Compiler
TBA

## Resources
* [https://interpreterbook.com/](https://interpreterbook.com/)
* https://github.com/gnolang/gno
