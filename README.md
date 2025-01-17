# python_package_template
_Default files and structure for python package repositories (aimed at personal use)_

## installation
There are no PyPI releases. Neither are they planned.

### manual
For installation with pip directly from this GitHub repository simply open a terminal and type
```
pip install git+ssh://git@github.com/rlipperts/python_package_template.git
```

### setup project environment for development
To setup this project to develop in it:
- Adjust template
    - edit this readme
    - change your package-name `src/package_name` and module name `src/package_name/module_name.py`
    - change the name of the test under `tests/test_module_name.py`
    - change the name of your project in the `pyproject.toml`
    - remove the template workflow under `.github/workflows/template_tests.yml`
- Setup poetry environment
    - `poetry lock`
    - `poetry install --with dev`
- Install the ruff pre-commit hooks
    - `poetry run pre-commit install`

## usage

Write a more or less detailed description on how to use your package!
