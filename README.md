<div align="center">

# Spell Checking System

### Binary Search Tree Dictionary Lookup in C

[![C](https://img.shields.io/badge/C-Data%20Structures-A8B9CC?logo=c&logoColor=black)](https://en.cppreference.com/w/c)

</div>

## Overview

This console application loads an English dictionary into a binary search tree, checks each word in a user-entered sentence, and suggests nearby dictionary words for misspellings.

## How It Works

1. Reads `EN-US-Dictionary.txt` into a case-insensitive binary search tree.
2. Reports dictionary size and tree height.
3. Tokenizes a typed sentence by spaces.
4. Marks words as correct or incorrect.
5. For an unrecognized word, prints nearby nodes based on predecessor/successor traversal.

## Repository Structure

```text
.
├── main.c                    # BST dictionary and checker implementation
├── EN-US-Dictionary.txt       # Dictionary word list
└── Ass.cbp                    # Code::Blocks project file
```

## Build and Run

```bash
gcc main.c -o spell-checker
./spell-checker
```

Keep `EN-US-Dictionary.txt` in the current working directory when launching the executable.

## Author

**Youssef Mohamed Attia**  
[GitHub](https://github.com/YoussefMohAttia) · [LinkedIn](https://www.linkedin.com/in/youssefmohattia/)
