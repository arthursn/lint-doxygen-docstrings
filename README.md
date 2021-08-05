# lint-doxygen-docstrings

Simple python3 tool for linting Doxygen docstrings

# Usage

```bash
usage: lint-doxygen-docstrings [-h] [-i] filenames [filenames ...]

Lints doxygen docstrings to standard notation

positional arguments:
  filenames      Filenames

optional arguments:
  -h, --help     show this help message and exit
  -i, --inplace  Inplace edit, if specified
```

## Example

```bash
lint-doxygen-docstrings -i file1.cpp file2.h file3.cxx
```