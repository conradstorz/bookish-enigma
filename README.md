
# Python Project Template

A low dependency and really simple to start project template for Python Projects.

See also [Flask-Project-Template](https://github.com/rochacbruno/flask-project-template/) for a full feature Flask project including database, API, admin interface, etc.


4. If you want [codecov](https://about.codecov.io/sign-up/) Reports and 
Automatic Release to [PyPI](https://pypi.org)  
  On the new repository `settings->secrets` add your `PIPY_API_TOKEN` and `CODECOV_TOKEN` (get the tokens on respective websites)

### What is included on this template?


- 📦 A basic [setup.py](setup.py) file to provide installation, packaging and distribution for your project.  
  Template uses setuptools because it's the de-facto standard for Python packages, you can run `make switch-to-poetry` later if you want.

- 🤖 A [Makefile](Makefile) with the most useful commands to install, test, lint, format and release your project.
- 📃 Documentation structure using [mkdocs](http://www.mkdocs.org)

- 💬 Auto generation of change log using **gitchangelog** to keep a HISTORY.md file automatically based on your commit history on every release.

- 🐋 A simple [Containerfile](Containerfile) to build a container image for your project.  
  `Containerfile` is a more open standard for building container images than Dockerfile, you can use buildah or docker with this file.

- 🧪 Testing structure using [pytest](https://docs.pytest.org/en/latest/)

- ✅ Code linting using [flake8](https://flake8.pycqa.org/en/latest/)

- 📊 Code coverage reports using [codecov](https://about.codecov.io/sign-up/)

- 🛳️ Automatic release to [PyPI](https://pypi.org) using [twine](https://twine.readthedocs.io/en/latest/) and github actions.

- 🎯 Entry points to execute your program using `python -m <bookish_enigma>` or `$ bookish_enigma` with basic CLI argument parsing.

- 🔄 Continuous integration using [Github Actions](.github/workflows/) with jobs to lint, test and release your project on Linux, Mac and Windows environments.

<!--  DELETE THE LINES ABOVE THIS AND WRITE YOUR PROJECT README BELOW -->

---
# bookish_enigma

[![codecov](https://codecov.io/gh/conradstorz/bookish-enigma/branch/main/graph/badge.svg?token=bookish-enigma_token_here)](https://codecov.io/gh/conradstorz/bookish-enigma)
[![CI](https://github.com/conradstorz/bookish-enigma/actions/workflows/main.yml/badge.svg)](https://github.com/conradstorz/bookish-enigma/actions/workflows/main.yml)

Awesome bookish_enigma created by conradstorz

## Install it from PyPI

```bash
pip install bookish_enigma
```

## Usage

```py
from bookish_enigma import BaseClass
from bookish_enigma import base_function

BaseClass().base_method()
base_function()
```

```bash
$ python -m bookish_enigma
#or
$ bookish_enigma
```

## Development

Read the [CONTRIBUTING.md](CONTRIBUTING.md) file.
