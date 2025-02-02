# Clox Language and Runtime

This codebase is an implementation of the `clox` language and runtime, as described in the third part of the book [_Crafting Interpreters_](https://craftinginterpreters.com/chunks-of-bytecode.html) by Robert Nystrom. This section of the book focuses on building a bytecode virtual machine for the Lox language, providing a deeper understanding of how interpreters work at a lower level.

## Overview

The `clox` implementation is a bytecode interpreter for the Lox language. It is designed to be efficient and portable, balancing simplicity and performance.

## Getting Started

To build and run the `clox` interpreter, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd clox
   ```

2. **Build the Project**:
   Use a C compiler to build the project. For example, using `gcc`:

   ```bash
   gcc -o clox main.c chunk.c memory.c debug.c value.c
   ```

3. **Run the Interpreter**:
   Execute the `clox` binary with a Lox script:
   ```bash
   ./clox script.lox
   ```

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

This implementation is based on the work of Robert Nystrom in his book [_Crafting Interpreters_](https://craftinginterpreters.com/chunks-of-bytecode.html). Special thanks to the author for providing such a comprehensive guide to building interpreters.
