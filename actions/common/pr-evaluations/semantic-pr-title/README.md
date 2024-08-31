# Semantic PR Check

Checks if the PR title follows semantic guidelines to ensure consistency and
readability.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Inputs](#inputs)

## Prerequisites

Ensure that the pull request titles follow semantic guidelines before using this
action. This includes starting the PR title with one of the allowed types (e.g.,
`fix`, `feat`, `docs`) and ensuring that the title does not exceed 50
characters.

## Inputs

| Name | Description | Required | Default |
|----------------|-----------------------------------------------|----------|---------|
| `github_token` | The GitHub token to use for authentication | Yes | N/A | |
`pr_title` | The title of the pull request | Yes | N/A |
