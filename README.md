# Kats for CoreStack


## Setup

- Require Python3.9 and Poetry


### To install poetry

`curl -sSL https://install.python-poetry.org | python3 -`


### To run unit tests

`poetry run pytest .`

### Contributing

Run `poetry install` to install the env.

Run `poetry run pre-commit install` to initialize the git hooks.

Run `poetry run pre-commit run --all-files` if there are file that were committed before adding the git hooks.
