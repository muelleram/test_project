# test_project

[![PyPI](https://img.shields.io/pypi/v/test_project.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/test_project.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/test_project)][pypi status]
[![License](https://img.shields.io/pypi/l/test_project)][license]

[![Read the documentation at https://test_project.readthedocs.io/](https://img.shields.io/readthedocs/test_project/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/muelleram/test_project/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/muelleram/test_project/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/test_project/
[read the docs]: https://test_project.readthedocs.io/
[tests]: https://github.com/muelleram/test_project/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/muelleram/test_project
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _test_project_ via [pip] from [PyPI]:

```console
$ pip install test_project
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [BSD 3 Clause license][License],
_test_project_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://test_project.readthedocs.io/en/latest/usage.html
[License]: https://github.com/muelleram/test_project/blob/main/LICENSE
[Contributor Guide]: https://github.com/muelleram/test_project/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/muelleram/test_project/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_test_project
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=html --jobs=auto --write-all; open _build/html/index.html
```