# Expenses

A self-hostable system for analyzing and visualizing expenses.

## Setup

After cloning, configure git to use the included hooks:

```sh
git config core.hooksPath .githooks
```

This enables the pre-commit hook which runs `vp staged` (format, lint, type-check) on client code and `dotnet format --verify-no-changes` on the API.
