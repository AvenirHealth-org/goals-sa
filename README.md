# goals-sa

[![Release](https://img.shields.io/github/v/release/avenirhealth-org/goals-sa)](https://img.shields.io/github/v/release/avenirhealth-org/goals-sa)
[![Build status](https://img.shields.io/github/actions/workflow/status/avenirhealth-org/goals-sa/main.yml?branch=main)](https://github.com/avenirhealth-org/goals-sa/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/avenirhealth-org/goals-sa/branch/main/graph/badge.svg)](https://codecov.io/gh/avenirhealth-org/goals-sa)
[![Commit activity](https://img.shields.io/github/commit-activity/m/avenirhealth-org/goals-sa)](https://img.shields.io/github/commit-activity/m/avenirhealth-org/goals-sa)
[![License](https://img.shields.io/github/license/avenirhealth-org/goals-sa)](https://img.shields.io/github/license/avenirhealth-org/goals-sa)

# Goals scenario analysis

- **Github repository**: <https://github.com/avenirhealth-org/goals-sa/>
- **Documentation** <https://avenirhealth-org.github.io/goals-sa/>

## Getting started with your project

### 2. Set Up Your Development Environment

Then, install the environment and the pre-commit hooks with

```bash
make install
```

This will also generate your `uv.lock` file

### 3. Run the pre-commit hooks

Initially, the CI/CD pipeline might be failing due to formatting issues. To resolve those run:

```bash
uv run pre-commit run -a
```

### 4. Commit the changes

Lastly, commit the changes made by the two steps above to your repository.

```bash
git add .
git commit -m 'Fix formatting issues'
git push origin main
```

You are now ready to start development on your project!
The CI/CD pipeline will be triggered when you open a pull request, merge to main, or when you create a new release.

To finalize the set-up for publishing to PyPI, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/codecov/).
