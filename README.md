# code-in-place
a repo to collect scripts related to Stanford's Code in Place, for which I am a director

## Setup

### Pre-requisites

- Python `3.12` or later
- `pyenv` - for Python version selection (REF)
- `pyenv-virtualenv` - for virtual environments (REF)
- `poetry` - for package management (REF)

### Developer Environment

n.b. keeping track of all the things i do for setup to be organized later

1. Create and activate a virtual environment for python with `pyenv`.

```commandline
$ pyenv virtualenv 3.12 code-in-place
$ pyenv activate code-in-place
$ pyenv version
code-in-place (set by PYENV_VERSION environment variable)
```

2. Install `poetry` and install packages.

```commandline
$ curl -sSL https://install.python-poetry.org | python -
$ poetry --version
Poetry (version 1.8.3)
$ poetry install
```

todo: add alternative, version-specific `poetry` installation step here

