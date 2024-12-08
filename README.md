# Lexical Analyzer (Lexer) for Arithmetic Expressions

![Lexical Analyzer](https://i.imgur.com/mnYQfzE.png)



This repository contains a **Lexical Analyzer** (or **Lexer**) implemented in Python, and is provided as a **Jupyter Notebook** (`.ipynb`). The lexer tokenizes arithmetic expressions into meaningful units called **tokens**. The tokens include identifiers, numbers, operators, parentheses, assignment operators, and semicolons. The lexer follows the **state machine** concept to identify and classify tokens from the input string.

## Features

- **Tokenization** of basic arithmetic expressions.
- Supports the following token types:
  - `IDENTIFIER`: Variable names (e.g., `x`, `y`)
  - `NUMBER`: Numeric values (e.g., `10`, `42`)
  - `ASSIGNMENT`: The assignment operator (`=`)
  - `OPERATOR`: Arithmetic operators (`+`, `-`, `*`, `/`)
  - `PARENTHESIS`: Parentheses (`(`, `)`)
  - `SEMICOLON`: The semicolon (`;`)
- Built-in **state machine** logic for handling the tokenization process.
- The code is provided in a Jupyter Notebook for easy execution and visualization.

## Getting Started

To run the notebook and explore the lexical analyzer, follow these steps:

### Prerequisites

- **Python 3.x** installed on your machine.
- **Jupyter Notebook** installed. If you don't have it, install it using:

  
  ```bash
  pip install notebook

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/vinukavinnath/lexical_analyzer.git

2. Open the `.ipynb` file in Jupyter Notebook.


### Testing
1. Add your preferred expression to `test_expressions` list.
2. Run the cell and observe the output.

![Testing](https://i.imgur.com/VXSyrxn.png)