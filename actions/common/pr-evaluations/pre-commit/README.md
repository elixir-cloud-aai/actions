# Pre-Commit Evaluations

Uses the `pre-commit` tool to run a series of checks on the repository before a
pull request is created. The checks are defined in the `.pre-commit-config.yaml`
file in the repository's root directory.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Inputs](#inputs)

## Prerequisites

Configure pre-commit hooks in root directory of the repository in
`.pre-commit-config.yaml` file. For example, look into [pre-commit config][pcc]
of cookiecutter-python repository.

## Inputs

N/A

[pcc]: https://github.com/elixir-cloud-aai/cookiecutter-python/blob/main/%7B%7B%20cookiecutter.project_name_dashed%20%7D%7D/.pre-commit-config.yaml
