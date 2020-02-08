# Sphinx

<img src="https://img.shields.io/pypi/v/sphinx.svg" alt="Package on PyPI"> <img src="https://readthedocs.org/projects/sphinx/badge/?version=master" alt="Documentation Status"> <img src="https://travis-ci.org/sphinx-doc/sphinx.svg?branch=master" alt="Build Status (Travis CI)"> <img src="https://ci.appveyor.com/api/projects/status/github/sphinx-doc/sphinx?branch=master&svg=true" alt="Build Status (AppVeyor)"> <img src="https://circleci.com/gh/sphinx-doc/sphinx.svg?style=shield" alt="Build Status (CircleCI)"> <img src="https://codecov.io/gh/sphinx-doc/sphinx/branch/master/graph/badge.svg" alt="Code Coverage Status (Codecov)"> <img src="https://img.shields.io/badge/License-BSD%203--Clause-blue.svg" alt="BSD 3 Clause">

Sphinx is a tool that makes it easy to create intelligent and beautiful
documentation for Python projects (or other documents consisting of multiple
reStructuredText sources), written by Georg Brandl.  It was originally created
for the new Python documentation, and has excellent facilities for Python
project documentation, but C/C++ is supported as well, and more languages are
planned.

Sphinx uses reStructuredText as its markup language, and many of its strengths
come from the power and straightforwardness of reStructuredText and its parsing
and translating suite, the Docutils.

Among its features are the following:

- Output formats: HTML (including derivative formats such as HTML Help, Epub
  and Qt Help), plain text, manual pages and LaTeX or direct PDF output
  using rst2pdf
- Extensive cross-references: semantic markup and automatic links
  for functions, classes, glossary terms and similar pieces of information
- Hierarchical structure: easy definition of a document tree, with automatic
  links to siblings, parents and children
- Automatic indices: general index as well as a module index
- Code handling: automatic highlighting using the Pygments highlighter
- Flexible HTML output using the Jinja 2 templating engine
- Various extensions are available, e.g. for automatic testing of snippets
  and inclusion of appropriately formatted docstrings
- Setuptools integration

For more information, refer to the [the documentation](http://www.sphinx-doc.org).

## Installation

Sphinx is published on [PyPI](https://pypi.org/project/Sphinx/) and can be installed from there:

```
   pip install -U sphinx
```

We also publish beta releases:

```
   pip install -U --pre sphinx
```

If you wish to install `Sphinx` for development purposes, refer to [the
contributors guide](http://www.sphinx-doc.org/en/master/devguide.html).

## Documentation

Documentation is available from [sphinx-doc.org](http://www.sphinx-doc.org/).

## Get in touch

- Report bugs, suggest features or view the source code [on GitHub](sphinx).
- For less well defined questions or ideas, use the [mailing list](https://groups.google.com/forum/#!forum/sphinx-users).

Please adhere to our [code of conduc](http://www.sphinx-doc.org/en/master/code_of_conduct.html).

## Testing

Continuous testing is provided by [Travis](https://travis-ci.org/sphinx-doc/sphinx)(for unit tests and style checks on Linux),[AppVeyor](https://ci.appveyor.com/project/sphinxdoc/sphinx)(for unit tests on Windows), and [CircleCI](https://circleci.com/gh/sphinx-doc/sphinx)(for large processes like TeX compilation).

For information on running tests locally, refer to [the contributors guide](http://www.sphinx-doc.org/en/master/devguide.html).

## Contributing

Refer to [the contributors guide](http://www.sphinx-doc.org/en/master/devguide.html).

## Release signatures

Releases are signed with following keys:

- [498D6B9E](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x102C2C17498D6B9E)
- [5EBA0E07](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x1425F8CE5EBA0E07)
