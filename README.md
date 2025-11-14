This repository serves as a base for a Python project

# Install
Check pre-requisites before running the following
```
git clone git@github.com:MBlogs/pybase.git
cd pybase
uv sync
uv run pybase/main.py
```

# Python Tool Commands
All to be run from inside the Python .venv first
```
source .venv/bin/activate
```

Linting and formatting
```
ruff check 
```
Type checking
```
ty check
```
Dependency checking
```
deptry .
```
Run python tests
```
pytest  # run python tests
```
Generate documentation
```
mkdocs serve  
```