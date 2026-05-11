## Prerequisites

This project uses [uv](https://docs.astral.sh/uv/) for fast and reproducible Python management. You don't need to manually install Python or manage virtual environments; uv handles it all.
Install uv:
https://docs.astral.sh/uv/getting-started/installation/

## Quick Start

1.  Clone the repository:

git clone <your-repo-url>
cd <project-folder>

2.  Sync the environment:
    Run the following command to automatically install the correct Python version and all dependencies into a local .venv:
```
uv sync
```
4.  Run the code:

- For scripts: uv run main.py
- For notebooks: Open your .ipynb file in VS Code and select the kernel located in .venv/bin/python (or .venv/Scripts/python.exe on Windows).

## Adding Dependencies

If you need to add a new package, use:
```
uv add <package-name>
```
This updates the pyproject.toml and uv.lock files automatically.
