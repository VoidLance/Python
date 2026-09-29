# Python Learning Scripts

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A small collection of standalone Python exercises covering basic input, classes,
arithmetic, comparisons, and random-number generation. Each script is
intended to be run independently and uses only the Python standard library.

## Contents

- [Why use this repository?](#why-use-this-repository)
- [Getting started](#getting-started)
- [Available scripts](#available-scripts)
- [Getting help](#getting-help)
- [Maintainers and contributing](#maintainers-and-contributing)
- [License](#license)

## Why use this repository?

These examples are useful for:

- Practising Python fundamentals with short, readable programs.
- Experimenting with console input and output.
- Learning introductory functions, classes, conditionals, and the `random`
  module.
- Starting with small examples that require no third-party dependencies.

## Getting started

### Requirements

- Python 3. No external packages are required.

### Run a script

Clone the repository, change into its directory, and run any script with
Python:

```bash
git clone https://github.com/VoidLance/Python.git
cd Python
python3 calculator.py
```

On Windows, use `py` or `python` if `python3` is not available:

```powershell
py calculator.py
```

The calculator and personal information card prompt for input. The other
examples print their results immediately.

## Available scripts

| Script | Description |
| --- | --- |
| [`calculator.py`](calculator.py) | Adds, subtracts, or multiplies two numbers entered at the prompt. |
| [`Personal Information Card.py`](Personal%20Information%20Card.py) | Collects personal details and displays them using a `Person` class. |
| [`Product Price Checker.py`](Product%20Price%20Checker.py) | Compares two product prices and reports which is higher. |
| [`Random Number Generator.py`](Random%20Number%20Generator.py) | Generates and displays random integer, float, and complex values. |

For example, to run the random-number example:

```bash
python3 "Random Number Generator.py"
```

The individual scripts have also been split into their own repositories for
focused use:

- [Calculator](https://github.com/VoidLance/course-files-python-calculator)
- [Personal Information Card](https://github.com/VoidLance/course-files-python-personal-information-card)
- [Product Price Checker](https://github.com/VoidLance/course-files-python-product-price-checker)
- [Random Number Generator](https://github.com/VoidLance/course-files-python-random-number-generator)

## Getting help

For questions or suspected bugs, search existing
[issues](https://github.com/VoidLance/Python/issues) first, then open a new
issue with:

- The script and Python version involved.
- The command you ran.
- The input used, if applicable.
- The complete error message or unexpected output.

The repository's [`SPLIT_FILE_REPOS.md`](SPLIT_FILE_REPOS.md) file contains the
mapping between these examples and their focused repositories.

## Maintainers and contributing

This project is maintained by [VoidLance](https://github.com/VoidLance).

Contributions are welcome. To propose a change:

1. Fork the repository and create a focused branch.
2. Keep examples dependency-free and runnable with Python 3.
3. Run the changed script(s) locally and update documentation when behavior
   changes.
4. Open a pull request describing what changed and how it was tested.

## License

This project is available under the [MIT License](LICENSE).
