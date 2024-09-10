# Welcome to EvoGenesis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/MaHaWo/EvoGenesis/ci.yml?branch=main)](https://github.com/MaHaWo/EvoGenesis/actions/workflows/ci.yml)
[![Documentation Status](https://readthedocs.org/projects/EvoGenesis/badge/)](https://EvoGenesis.readthedocs.io/)
[![codecov](https://codecov.io/gh/MaHaWo/EvoGenesis/branch/main/graph/badge.svg)](https://codecov.io/gh/MaHaWo/EvoGenesis)

## Installation

The Python package `EvoGenesis` can be installed from PyPI:

```
python -m pip install EvoGenesis
```

## Development installation

If you want to contribute to the development of `EvoGenesis`, we recommend
the following editable installation from this repository:

```
git clone https://github.com/MaHaWo/EvoGenesis
cd EvoGenesis
python -m pip install --editable .[tests]
```

Having done so, the test suite can be run using `pytest`:

```
python -m pytest
```

## Acknowledgments

This repository was set up using the [SSC Cookiecutter for Python Packages](https://github.com/ssciwr/cookiecutter-python-package).
