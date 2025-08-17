# torch-project-template

This is a template for a project that uses PyTorch.

## How to use

1. Create your project directory (i.e. create and clone a repo from github, or locally)
2. Copy the contents of this repo into your project directory
3. Update the `pyproject.toml` file with your project details
4. Update the `README.md` file with your project details


## Installation

```bash
uv sync
```

## Running the project

```bash
# install with pytorch cpu
uv sync --extra cpu
# install dev dependencies
uv sync --dev --extra cpu
# install with pytorch cu121
uv sync --extra cu121
# install with pytorch cu124
uv sync --extra cu124
```