# Hugging Face LLM Course

## Setup (One-time)

Create and install the virtual environment with all dependencies:
```bash
pipenv install
```

This will:
- Create an isolated virtual environment
- Install all packages from `Pipfile`
- Generate `Pipfile.lock` for reproducible builds

## Running the project

### Option 1: Run individual commands
```bash
pipenv run python src/main.py
```

### Option 2: Enter the environment shell
```bash
pipenv shell
python src/main.py
```

## Managing dependencies

### Install new packages
```bash
pipenv install package-name
```

### Install development dependencies
```bash
pipenv install package-name --dev
```

### Show virtual environment info
```bash
pipenv --venv    # Show environment path
pipenv --py      # Show Python interpreter path
```