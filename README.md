# Compiler Project

## Introduction
This project involves the development of a simple compiler for C++ code, executed in three distinct phases: Lexical Analysis, Top-Down Parsing, and Three-Address Code Generation. Each phase builds upon the previous one, refining and expanding the compiler’s capabilities. By the end of the project, we achieved a functional compiler capable of generating intermediate three-address code from simple C++ source code.

## Project Phases

### Phase 1: Lexical Analyzer
The first phase focused on developing a lexical analyzer. The main tasks completed during this phase were:

- **Tokenization**: Scanned the input C++ source code and converted it into a sequence of tokens, including keywords, identifiers, and operators.
- **Regular Expressions**: Defined the patterns for different tokens using regular expressions.

### Phase 2: Top-Down Parser
The second phase focused on developing a top-down parser, specifically a recursive descent parser. Key tasks accomplished included:

- **Grammar Definition**: Defined the context-free grammar (CFG) for a subset of the C++ language. This grammar was designed to be LL(1) to facilitate top-down parsing.
- **Parser Implementation**: Implemented a recursive descent parser using the CFG. The parser takes the token stream produced by the lexical analyzer and constructs a parse tree.

### Phase 3: Three-Address Code Generator
In the final phase, the compiler was extended to generate three-address code (TAC), an intermediate representation of the source code. Key developments in this phase were:

- **Grammar Refinement**: Modified the grammar defined in the second phase to better suit the needs of code generation.
- **Parse Tree to TAC Conversion**: Developed algorithms to traverse the parse tree and generate corresponding three-address code.
- **Optimization**: Implemented basic optimizations to produce more efficient intermediate code.

## Conclusion
This project culminated in a fully functional simple C++ compiler capable of performing lexical analysis, parsing, and generating three-address code. The iterative development approach ensured that each phase built upon the previous one, leading to a coherent and integrated compiler.

## Usage
To use the compiler, follow these steps:

1. **Lexical Analysis**: Run the lexical analyzer to tokenize the input C++ source code.
2. **Parsing**: Use the top-down parser to construct a parse tree from the tokenized input.
3. **Code Generation**: Generate three-address code from the parse tree.

For detailed instructions on each phase, refer to the project documentation.

## Live Demo
Check out the live demo of the compiler [here](https://kiana8181.github.io/Compiler/).
