# UV

Uv is an all-in-one tool for python.

- [website](https://docs.astral.sh/uv/)
- [github](https://github.com/astral-sh/uv)

| command | description |
| --- | --- |
| `uv init` | Initialize a python project, creating a `pyproject.toml` file |
| `uv sync` | Installs correct python version, creates venv and installs dependencies defined in the `pyproject.toml` file. |
| `uv run` | Executes a python script in the environment defined in the `pytproject.toml` file. |
| `uv add` | Adds a dependency |
| `uv remove` | Removes a dependency |

A little bit more advanced

| command | description |
| --- | --- |
| `uv add --dev` | Adds a dependency to the `dev` group. Only the main and the `dev` groups are installed by default when running `uv sync` |
| `uv init --package` | Initialized pyproject with a default [build-system] entry |


