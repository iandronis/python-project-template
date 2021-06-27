# Python Project Template

This is a repo template to use as a baseline and start a new python project.
The template includes some useful packages along with a dummy setup to serve
a draft documentation version.

## Code Cleaning

To have a more clear and robust code, there are some common packages that most
of the python projects are using:

* [flake8] - Style guide tool
* [black] - Python code formatter
* [isort] - Sort imports tool
* [pylint] - Static code analysis tool
* [gitlint] - Commit message linter
* [pytest] - Start the live-reloading docs server
* [safety] - Check security vulnerabilities tool

In order to apply those, some relative **pre-commit hooks** have been added.

## Documentation

For the documentation, I propose using Markdown files along with [Mkdocs].  
At this doc, you may find some [examples](./markdown_examples.md), which you
could use.

[flake8]: https://github.com/PyCQA/flake8
[black]: https://github.com/psf/black
[isort]: https://github.com/PyCQA/isort
[pylint]: https://github.com/PyCQA/pylint
[gitlint]: https://github.com/jorisroovers/gitlint
[pytest]: https://github.com/pytest-dev/pytest
[safety]: https://github.com/pyupio/safety
[Mkdocs]: https://www.mkdocs.org/
