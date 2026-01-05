# ELIZA Assignment Repository

**Parent:** [llm-course](https://github.com/ContextLab/llm-course) (see main AGENTS.md)

## Overview

Assignment 1 template repository for PSYC 51.17. Students implement the classic ELIZA chatbot using pattern matching and string manipulation.

## Structure

```
eliza-llm-course/
├── Assignment1_ELIZA.ipynb  # Template notebook (has Colab badge)
├── instructions.txt         # ELIZA rules file
├── README.md               # Assignment description
└── AGENTS.md               # This file
```

## Key Files

| File | Purpose |
|------|---------|
| `Assignment1_ELIZA.ipynb` | Student-facing notebook with Colab badge |
| `instructions.txt` | Pattern/response rules parsed by student code |

## Conventions

- Notebook opens in Colab via badge at top
- Students fork via GitHub Classroom, not direct clone
- Autograder runs from private teaching-tools repo

## Anti-Patterns

- Don't commit solution code to this repo (template only)
- Don't modify instructions.txt format (breaks student parsers)
