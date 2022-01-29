# Contribute

## Prerequirement

- pyenv
- poetry

### Windows

https://qiita.com/kerobot/items/3f4064d5174676080585#python-%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB

### Mac

https://qiita.com/tama0571046/items/1c411a44b2f9caf6edb3

## Setup

1. Set Python virtual environment

```
pyenv install 3.9.5
pyenv local 3.9.5
```

1. Install dependencies

```
poetry config virtualenvs.in-project true
poetry install
pre-commit install # must execute, MUST EXECUTE!!
```

1. Install VSCode extension

Follow the recommended extensions, see below.

https://code.visualstudio.com/docs/editor/extension-marketplace#_workspace-recommended-extensions
