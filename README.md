# python-continuous-integration

## linter

Library used: [flake8](http://flake8.pycqa.org/en/latest/)

- Run linter: `flake8 <folder-name or file-name>`, ex: `flake8 calculator.py`

## test

Library used: [pytest](https://docs.pytest.org/en/latest/)

- Run tests:  `pytest -v --cov`

    - The `-v` flag gives you a nicer output, telling you which tests passed and which failed.
    - The `--cov` flag makes sure `pytest-cov` runs and gives you a code coverage report. 