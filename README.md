# Quadratic Equations Solver

This module solves Quadratic Equations

# Usage Example

```python
from quadratic_equation import get_roots

print(get_roots(1, 2, 3))
```

# pre-commit hook usage

This module have pre-commit hook file:
If tests will fail - commit won't be accepted
First you must configure it:

Open pre-commit file in module directory

```sh
# Set your paths
pathToTest="path_to_tests.py"
pathToPython="path_to_python.exe"

```

After that - save it to ./git/hooks directory in module directory

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
