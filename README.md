# uv_example

UV Example Project

## Overview

This project demonstrates a Python development workflow using [uv](https://docs.astral.sh/uv/), a fast Python package manager and virtual environment tool. The repository includes a `Makefile` to automate common tasks such as installing dependencies, linting, formatting, and running tests. The setup is intended to provide a reproducible and efficient environment for Python development.

## Features

- **Automated Environment Setup:** Quickly create and manage a virtual environment using `uv`.
- **Dependency Management:** Compile and install dependencies from `pyproject.toml`.
- **Code Quality:** Integrated linting and formatting with [ruff](https://docs.astral.sh/ruff/) and type checking with [mypy](https://mypy-lang.org/).
- **Testing:** Run all tests using [pytest](https://pytest.org/).
- **Easy Commands:** Use `make` targets for common development tasks.

## Getting Started

1. Install [uv](https://docs.astral.sh/uv/getting-started/installation/).
2. Run `make install` to set up the environment and install dependencies.
3. Use `make lint`, `make format`, and `make test` to maintain code quality and run tests.

See the `Makefile` for more details on available commands.
