# chumpy

Autodifferentiation tool for Python.

_Repackaged with poetry._

## Installation

```bash
pip install chumpy
```

## Overview

Chumpy is a Python-based framework designed to handle the **auto-differentiation** problem,
which is to evaluate an expression and its derivatives with respect to its inputs, by use of the chain rule.

Chumpy is intended to make construction and local
minimization of objectives easier.

Specifically, it provides:

- Easy problem construction by using Numpy’s application interface
- Easy access to derivatives via auto differentiation
- Easy local optimization methods (12 of them: most of which use the derivatives)

## Usage

Chumpy comes with its own demos, which can be seen by typing the following:

```python
import chumpy
chumpy.demo() # prints out a list of possible demos
```

## License

This project is licensed under the MIT License.

## Development

```bash
poetry run pytest -s
```
