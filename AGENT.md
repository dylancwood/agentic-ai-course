# AGENT.md

## Project Overview

This repository contains course materials for learning about agentic AI patterns and techniques. The primary content is Jupyter notebooks covering topics like function/tool calling APIs, Python integration patterns, and hands-on examples.

## Repository Structure

```
├── README.md
├── notebooks/
│   ├── colab-sample.ipynb          # Sample Colab notebook setup
│   ├── function-apis.ipynb         # Core: function/tool calling APIs
│   ├── function-apis-extra-credit.ipynb  # Extended exercises
│   ├── module-1-example.ipynb      # Module 1 walkthrough
│   ├── python-calls.ipynb          # Python function calling patterns
│   └── test_dir/                   # Test fixtures
```

## Conventions

- **Language**: Python (Jupyter notebooks)
- **Primary format**: `.ipynb` — all instructional content lives in notebooks
- **Branch strategy**: `main` is the default branch; use feature branches for changes

## Working with This Repo

- Do not modify notebook outputs unless explicitly asked — outputs may be intentionally preserved for instructional purposes.
- When adding new notebooks, follow the existing naming convention: lowercase, hyphen-separated (e.g., `new-topic-name.ipynb`).
- Keep notebook cells focused and well-commented for readability by learners.
- If adding dependencies, note them in a code cell at the top of the notebook (e.g., `!pip install ...`).

## Testing

There is no formal test suite. Notebooks should be manually validated by running all cells top-to-bottom in a clean kernel.

## Style Guidelines

- Use clear, beginner-friendly explanations in Markdown cells.
- Prefer explicit over clever code — this is educational material.
- Include inline comments for non-obvious logic.
- Add section headers (Markdown `##`) to break notebooks into logical segments.
