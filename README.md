# example-project-python
Example python project

[![Build Status](https://github.com/ColumbiaOSS/example-project-python/workflows/Build%20Status/badge.svg?branch=main)](https://github.com/ColumbiaOSS/example-project-python/actions?query=workflow%3A%22Build+Status%22)
[![codecov](https://codecov.io/gh/ColumbiaOSS/example-project-python/branch/main/graph/badge.svg)](https://codecov.io/gh/ColumbiaOSS/example-project-python)
[![PyPI](https://img.shields.io/pypi/v/example-project-python)](https://pypi.org/project/example-project-python/)

## Details
This project is a pure python project using modern tooling. It uses a `Makefile` as a command registry, with the following commands:
- `make`: list available commands
- `make develop`: install and build this library and its dependencies using `pip`
- `make build`: build the library using `setuptools`
- `make lint`: perform static analysis of this library with `flake8` and `black`
- `make format`: autoformat this library using `black`
- `make annotate`: run type checking using `mypy`
- `make test`: run automated tests with `pytest`
- `make coverage`: run automated tests with `pytest` and collect coverage information
- `make dist`: package library for distribution

