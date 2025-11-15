This repository serves as a base for a Python project

# Install
Check pre-requisites before running the following in root
```bash
uv sync
uv run pybase/main.py
```

# Python Tool Commands
All to be run from inside the Python .venv first
```bash
source .venv/bin/activate
```

Linting and formatting
```bash
ruff check 
```
Type checking
```bash
ty check
```
Dependency checking
```bash
deptry .
```
Run python tests
```bash
pytest
```
Generate documentation
```bash
mkdocs serve  
```

# Continuous Integration
The above checks are ran as a pre-commit hook.
To trigger manually:
```bash
pre-commit run --all-files
```
Github actions set to manual invoke only.
Can add to automatically on push in: 
```
.github/workflows/github-actions.yaml
```