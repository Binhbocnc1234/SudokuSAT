# Project Instructions

## Project Brief

SudokuSAT solves generalized Sudoku using SAT and compares SAT with constraint programming and integer programming. This folder is the Git repository; the enclosing course-material workspace is not part of this repository.

## Documentation Entry Point

Read [README.md](README.md) for setup, source layout, benchmark commands, and paper generation. The README is the documentation entry point; no separate documentation index is configured. Dependency versions are defined in [requirements.txt](requirements.txt).

## Python Environment and Verification

Run commands from this repository root. Create the local Python environment using the setup commands in the README.

Run the workflow tests with:

```bash
.venv/bin/python -m pytest -q tests
```

Benchmark scripts use `.venv/bin/python`. The scripts replace the corresponding CSV files under `results/`, so running a benchmark changes recorded experiment data. The README names the benchmark and report-generation entry points.

Gurobi requires a license; the CPLEX Community Edition has model-size limits described in the README. Keep license files and credentials out of Git.

## Initial Publication Contract

The initial public repository MUST contain exactly one archive-import commit. Amend the import commit for changes belonging to this initial publication rather than adding a second commit.

Why: the developer requested public publication with only one commit.
