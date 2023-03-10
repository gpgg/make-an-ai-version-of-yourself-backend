# Make an AI version of yourself (backend)

## Usage

```
poetry update
```

Then start `video_server.ipynb` and `demo.ipynb`

## Tools

- pyenv: python version management.

use pyenv to set the python version:

```python
pyenv local 3.8.10
```

- poetry: dependency management.

poetry config settings:

```python
virtualenvs.in-project = true # poetryの仮想環境をプロジェクトと同一フォルダに配置する
virtualenvs.prefer-active-python = true # Poetry will try to find the current python of your shell.
```
