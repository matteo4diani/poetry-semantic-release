![Tests](https://github.com/matteo4diani/poetry-semantic-release-test/actions/workflows/test.yml/badge.svg)
![Release](https://github.com/matteo4diani/poetry-semantic-release/actions/workflows/release.yml/badge.svg)

# semantic-poetry 🪶
[semantic-poetry](https://github.com/marketplace/actions/semantic-poetry) is a GitHub Action that automates the release of [poetry](https://python-poetry.org/)-based Python packages on GitHub and PyPI following [semantic versioning](https://semver.org) and [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) standards.

## Usage

To use it in your CI:
1. Generate a PyPI Token from PyPI: https://pypi.org/help/#apitoken
2. Set your PyPI Token as a repository secret named `PYPI_TOKEN`: https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository
3. For a quick start copy the `[tool.semantic_release]` section of this [pyproject.toml](https://github.com/matteo4diani/poetry-semantic-release-test/blob/main/pyproject.toml) and adjust it to your needs.
4. For advanced semantic-release configurations: https://python-semantic-release.readthedocs.io/en/latest/configuration.html#configuration

Happy hacking 😼

## Tests

Test runs can be found at https://github.com/matteo4diani/poetry-semantic-release-test/actions, which is a sample poetry-based Python project used to test this action.

## Tools

This action uses [poetry](https://python-poetry.org/) and [python-semantic-release](https://python-semantic-release.readthedocs.io/en/latest/index.html). 

