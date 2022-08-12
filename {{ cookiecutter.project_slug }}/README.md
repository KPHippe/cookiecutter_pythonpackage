# {{ cookiecutter.project_name}}

<!-- TODO: Add badges -->
<!-- [![PyPI version](https://badge.fury.io/py/mdlearn.svg)](https://badge.fury.io/py/mdlearn) -->
<!-- [![Documentation Status](https://readthedocs.org/projects/mdlearn/badge/?version=latest)](https://mdlearn.readthedocs.io/en/latest/?badge=latest) -->

{{cookiecutter.project_short_description}}

For more details and specific examples of how to use {{ cookiecutter.project_slug}}, please see our [documentation](https://readthedocs.org/).

## Table of Contents
- [{{ cookiecutter.project_slug }}](#{{ cookiecutter.project_slug.replace("_", "-") if " " in cookiecutter.project_name else cookiecutter.project_name.replace("_", "")}})
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
    - [Install latest version with PyPI](#install-latest-version-with-pypi)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Acknowledgments](#acknowledgments)
  - [License](#license)

## Installation

### Install latest version

```
git clone https://github.com/{{cookiecutter.github_username}}/{{ cookiecutter.project_slug }}.git
pip3 install -r requirements/requirements.txt
pip3 install .
``` 

### Installing in `develop` mode
*Recomended to use conda virtual environment*
```
conda create -n [env_name] python={{cookiecutter.python_version}}
pip3 install --upgrade pip setuptools wheel
pip3 install -r requirements/dev.txt
pip3 install -r requirements/requirements.txt
pip3 install -e .

## Usage

TODO

## Contributing

Please report **bugs**, **enhancement requests**, or **questions** through the [Issue Tracker](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/issues).

If you are looking to contribute, please see [`CONTRIBUTING.md`](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/blob/main/CONTRIBUTING.md).


## Acknowledgments

TODO

## License

<!-- {{ cookiecutter.project_slug }} has a TODO license, as seen in the [LICENSE](https://github.com/ramanathanlab/mdlearn/blob/main/LICENSE) file. -->
