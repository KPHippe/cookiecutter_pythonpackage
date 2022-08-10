# Cookiecutter python package 

This is a repo to create a python package from a template 

*Inspired by setup from Alex Brace*

### Instructions 

1. Create virtual environment 
    ```bash
    conda create -n [env_name] python=[python_version]
    conda activate [env_name]
    pip install cookiecutter
    ```
1. Run command `cookiecutter https://github.com/KPHippe/cookiecutter_pythonpackage.git` and follow setup prompt
1. For documentation, after installation, run `cd docs && make html`. This will populate the autodocumentation and allow you to see the docs files at `docs/build/html/index.html`

### Notes 
* This does *not* initialize a git repo, you will have to do this yourself. 

# Things included 
* `README.md`
* `CONTRIBUTING.md`
* `CODE_OF_CONDUCT.md`
* `Makefile`
    * Contains infrastructure for black, flake8, pytest, and mypy
* `requirements/`
    * contains install `dev.txt` for dev tools 
* `setup.cfg` and `setup.py` to install as a package 
* Place to put tests (`test`), and an initial test completed for you 
* Place to put documentation (`docs`)
* Github issue templates 
* Github action for linting and testing 
* Sphinx autodocumentation 