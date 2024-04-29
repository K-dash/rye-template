
# Python Project Template for Rye

This is a template that can be used generically for projects.
As a package management tool, Rye is used.

## Prerequisites
Before using this template, please ensure the following software is installed:

[Rye: Package management tool.](https://github.com/mitsuhiko/rye)
The following command allows you to install Rye:
```
curl -sSf https://rye-up.com/get | RYE_INSTALL_OPTION="--yes" bash
echo 'source "$HOME/.rye/env"' >> ~/.bashrc
source "$HOME/.rye/env"
```

The following dependencies will be automatically installed using Rye:
- Python 3.10.x (latest)
- Python Libraries
  -   The installed libraries are listed in the requirements.lock file.

## Usage
### Install the required packages.

```bash
make install
```

### To test the functionality, execute main.py.

```bash
make run_main
```

### Execute pre-commit

```bash
make pre-commit
```
