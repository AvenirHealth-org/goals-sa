# goals-sa

[![Release](https://img.shields.io/github/v/release/avenirhealth-org/goals-sa)](https://img.shields.io/github/v/release/avenirhealth-org/goals-sa)
[![Build status](https://img.shields.io/github/actions/workflow/status/avenirhealth-org/goals-sa/main.yml?branch=main)](https://github.com/avenirhealth-org/goals-sa/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/avenirhealth-org/goals-sa/branch/main/graph/badge.svg)](https://codecov.io/gh/avenirhealth-org/goals-sa)
[![Commit activity](https://img.shields.io/github/commit-activity/m/avenirhealth-org/goals-sa)](https://img.shields.io/github/commit-activity/m/avenirhealth-org/goals-sa)
[![License](https://img.shields.io/github/license/avenirhealth-org/goals-sa)](https://img.shields.io/github/license/avenirhealth-org/goals-sa)

# Goals scenario analysis

- **Github repository**: <https://github.com/avenirhealth-org/goals-sa/>
- **Documentation** <https://avenirhealth-org.github.io/goals-sa/>

## Development

### Prerequisites

* [uv](https://docs.astral.sh/uv/) for installing Python, package management
* (Optionally) [make](https://www.gnu.org/software/make/). Should be installed by default except on windows where proabably easiest to install it via [Chocolatey](https://chocolatey.org/install) `choco install make`

### Development with make

There is a `Makefile` which wraps some common `uv` commands you will need during development.

#### Set Up Your Development Environment

Install the environment and the pre-commit hooks with

```bash
make install
```

This will also generate your `uv.lock` file.

#### Run code checks

```bash
make check
```

#### Run tests

```bash
make test
```

#### Build docs site

```bash
make docs
```

### Development with uv

If you choose not to use make, you can use `uv` directly.

### Set Up Your Development Environment

Install the environment and the pre-commit hooks with

```bash
uv sync
uv run pre-commit install
```

This will also generate your `uv.lock` file.

### Run code checks

Run pre-commit checks, include ruff linting and formatting

```bash
uv run pre-commit run -a
```

Run type checking

```bash
uv run ty check
```

### Run tests

```bash
uv run pytest
```

### Build docs site

```bash
uv run mkdocs serve
```
