# Mini Compiler and Interpreter in C++

This project is a simple compiler and interpreter for a custom programming language implemented in C++. It demonstrates the core phases of compiler design, including lexical analysis, parsing, Abstract Syntax Tree (AST) generation, interpretation, and code generation.

## Features

* Lexical Analysis (Tokenization)
* Recursive Descent Parser
* Abstract Syntax Tree (AST) Construction
* Expression Evaluation
* Variable Declaration and Assignment
* Arithmetic and Comparison Operations
* Conditional Statements (if/else)
* Looping Constructs (while, for)
* Break and Continue Support
* Runtime Error Handling
* Code Generation Support

## Project Architecture

Lexer → Parser → AST → Interpreter / Code Generator

### Components

* **lexer.h** – Converts source code into tokens.
* **utils.h** – Utility functions and helper methods.
* **ast.h** – Defines AST node structures.
* **parser.h** – Implements a Recursive Descent Parser to build the AST.
* **interpreter.h** – Executes the AST and handles program runtime behavior.
* **codegen.h** – Generates target code from the AST.
* **main.cpp** – Entry point of the application.

## Technologies Used

* C++
* Object-Oriented Programming
* Abstract Syntax Trees (AST)
* Recursive Descent Parsing
* Standard Template Library (STL)

## Learning Outcomes

This project helped us understand the internal working of compilers, including tokenization, syntax analysis, semantic execution, runtime evaluation, and code generation techniques.
