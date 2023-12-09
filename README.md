# cookiecutter-advent-of-code-python-TDD

<!-- [![PyPI - Version](https://img.shields.io/pypi/v/advent-of-code-python-tdd-template.svg)](https://pypi.org/project/advent-of-code-python-tdd-template) -->
<!-- [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/advent-of-code-python-tdd-template.svg)](https://pypi.org/project/advent-of-code-python-tdd-template) -->

This project was born after 9 days of doing the same things over and over before starting the actual challenges.

This cookiecutter template provides a framework to rapidly set up
the folder structure for your [Advent of Code](https://en.wikipedia.org/wiki/Advent_of_Code) repo. This means that initial prompts can be downloaded via [`make`](https://en.wikipedia.org/wiki/Make_(software)), and skeletons for main module and tests will be set each day, saving you the hustle of coding this boilerplate manually everyday.

-----

**Table of Contents**

- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)

## Requirements

This project assume an opinionated stance on Python's main packaging tool by adopting [`hatch`](https://hatch.pypa.io/latest/). This may change in the future, but let's hope it won't.

Other dependencies are:

- [cruft](https://cruft.github.io/cruft/)/[cookiecutter](https://www.cookiecutter.io/) for adapting metadata to **your** needs;
- [curl](https://curl.se/) to fetch resources;
- [GNU make](https://www.gnu.org/software/make/) to manage the workflows;
- [pandoc](https://pandoc.org/) to translate prompts from HTML to []GitHub Flavored Markdown](https://github.github.com/gfm/)


## Installation

### Cruft is the way!

The simplest method to start is by "crufting" this repo: 

    $ cruft create https://github.com/ninoCan/cookiecutter-advent-of-code-python-TDD.git

There you go start coding!

### ...but if you prefer cookies...

Alternatively, if you don't have cruft and just want to use cookiecutter, go ahead and clone this repo:

    $ git clone https://github.com/ninoCan/cookiecutter-advent-of-code-python-TDD.git 


Modify the variables defined in cookiecutter.json.
Open up the skeleton project.
If you need to change it around a bit, do so.
Then generate your project from the project template:

$ cookiecutter cookiecutter-advent-of-code-python-TDD

Try it out!


## License

`cookiecutter-advent-of-code-python-tdd` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
