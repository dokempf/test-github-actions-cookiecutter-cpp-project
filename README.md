# Welcome to My C++ Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



[![PyPI version](https://badge.fury.io/py/testgithubactionscookiecuttercppproject.svg)](https://badge.fury.io/py/testgithubactionscookiecuttercppproject)
[![Documentation Status](https://readthedocs.org/projects/test-github-actions-cookiecutter-cpp-project/badge/?version=latest)](https://test-github-actions-cookiecutter-cpp-project.readthedocs.io/en/latest/?badge=latest)

# Prerequisites

Building My C++ Project requires the following software installed:

* A C++11-compliant compiler
* CMake `>= 3.9`
* Doxygen (optional, documentation building is skipped if missing)
* Python `>= 3.6` for building Python bindings

# Building My C++ Project

The following sequence of commands builds My C++ Project.
It assumes that your current working directory is the top-level directory
of the freshly cloned repository:

```
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build .
```

# Documentation

My C++ Project provides a Sphinx-based documentation, that can
be browsed [online at readthedocs.org](https://test-github-actions-cookiecutter-cpp-project.readthedocs.io).

