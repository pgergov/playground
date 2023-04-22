# Playground

Exploring different tools and techniques.

## Getting Started

### Set up Python 3.11 with pyenv

Install `pyenv` using the instructions on the pyenv GitHub page: https://github.com/pyenv/pyenv#installation

```bash
brew update
brew install pyenv
```

Find latest Python 3.11 version:

```bash
pyenv install --list | grep 3.11
```

Install Python 3.11:

```bash
pyenv install 3.11.3
```

Create a virtual environment:

```bash
pyenv virtualenv 3.11.3 playground-3.11.3
```

Activate the environment:

```bash
pyenv activate playground-3.11.3
```

Upgrade pip:

```bash
python3.11 -m pip install --upgrade pip
```

Install requirements:

```bash
pip install -r requirements.txt
```

### Set up pre-commit hooks

Make sure pre-commit is installed:

```bash
pre-commit --version
```

Set up the git hook scripts:

```bash
pre-commit install
```

Set up the pre-commit environment:

```bash
pre-commit
```
