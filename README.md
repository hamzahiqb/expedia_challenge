# [Expedia challenge](https://www.kaggle.com/c/expedia-hotel-ranking-exercise)


## Local Development

To replicate environment in local:
1. Clone the repo
2. The project uses python 3.7.1 or higher.
3. For package and environment management, we use [poetry](https://python-poetry.org/):
    - Install poetry from [here](https://python-poetry.org/docs/#installation)
    - Run `poetry install` to install environment and packages in `pyproject.toml`
    - Run `poetry shell` to activate environment. (`exit` for exit the env)
    - To add/remove a package, run `poetry add/remove MY_PACKAGE`
4. (Really Optional) We use [pre-commit](https://pre-commit.com/) for linting, code-formatting right before git-commits:
    - Before every commit, this will make a formatting edits to .py files (sometimes others too)
    - It causes issues when files are both in staging and un-staged mode. Recommend staging all files before running pre-commit. Or just don't install it.
    - Run `poetry run pre-commit install` to activate it
4. Edit and commit as usual.
