# WZ-BIT-MiniCC
A compiler for a subset of C.<br>
From C to MIPS.<br>
Scan - Parse - Semantic - ICGen - NCGen<br>
Based on BIT-MiniCC Framework.

# BIT-MiniCC
BIT Mini C Compiler is a C compiler framework in Java for teaching.

## Building & Running
### Requirements
* JDK 1.8 or higher
* Eclipse Mars

### Building & Running
1. Import the project into Eclipse
2. Set the input source file
3. run as Java applications from class BitMiniCC

## Supported targets
1. x86
2. MIPS
3. RISC-V
4. ARM (coming soon)

## Lab. projects
1. Lexical Analysis: input(C code), output(tokens in JSON)
2. Syntactic Analysis: input(tokens in JSON), output(AST in JSON)
3. Semantic Analysis: input(AST in JSON), output(errors)
4. IR Generation: input(AST in JSON), output(IR)
5. Target Code Generation: input(AST in JSON), output(x86/MIPS/RISC-V assembly)
