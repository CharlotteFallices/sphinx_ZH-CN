# Sphinx

<img src="https://img.shields.io/pypi/v/sphinx.svg" alt="Package on PyPI"> <img src="https://readthedocs.org/projects/sphinx/badge/?version=master" alt="Documentation Status"> <img src="https://travis-ci.org/sphinx-doc/sphinx.svg?branch=master" alt="Build Status (Travis CI)"> <img src="https://ci.appveyor.com/api/projects/status/github/sphinx-doc/sphinx?branch=master&svg=true" alt="Build Status (AppVeyor)"> <img src="https://circleci.com/gh/sphinx-doc/sphinx.svg?style=shield" alt="Build Status (CircleCI)"> <img src="https://codecov.io/gh/sphinx-doc/sphinx/branch/master/graph/badge.svg" alt="Code Coverage Status (Codecov)"> <img src="https://img.shields.io/badge/License-BSD%203--Clause-blue.svg" alt="BSD 3 Clause">

Sphinx是由Georg Brandl编写的工具，可让您轻松地为Python项目（或由多个reStructuredText源组成的其他文档）创建智能且美观的文档。它最初是为新的Python文档创建的，具有用于Python项目文档的出色功能，但同时也支持C / C ++，并且计划了更多的语言。

Sphinx使用`reStructuredText`作为其标记语言，其许多优点来自`reStructuredText`及其解析和翻译插件`Docutils`的强大功能和直接性.

其功能包括:

- 输出格式:HTML(包括派生格式,例如`HTML help`,`Epub`和`Qt help`),`纯文本`,`manual pages`和`LaTeX`或使用`rst2pdf`的直接PDF输出.
- 广泛的交叉引用:功能,类,词汇术语(glossary terms)和类似信息的语义标记和自动链接
- 层次结构:定义文档树时自动链接到相关文件.
- 自动索引:常规索引以及模块索引.
- 代码处理:使用`Pygments语法高亮`**(highlighter)** 自动突出显示.
- 使用`Jinja 2`模板灵活地输出HTML.
- 提供扩展程序,例如用于自动测试代码片段并包含适当格式的字符串(docstrings).
- `Setuptools`集成.

有关更多信息，请参考[文档](http://www.sphinx-doc.org).

## Installation

正式版可以在[PyPI](https://pypi.org/project/Sphinx/)上安装:

```
   pip install -U sphinx
```

beta版请使用以下命令:

```
   pip install -U --pre sphinx
```

如果您是要处于开发`Sphinx`的目的而安装,请参考[开发者指南](http://www.sphinx-doc.org/en/master/devguide.html).

## Documentation

可以从[sphinx-doc.org](http://www.sphinx-doc.org/)获得帮助文档.

## Get in touch

- 请将bugs和feature提交到[GitHub](sphinx),您也可以在这里查看源代码.
- 不太明确的想法更建议发送至[mailing list](https://groups.google.com/forum/#!forum/sphinx-users).

也请您同时遵守我们的[行为准则](http://www.sphinx-doc.org/en/master/code_of_conduct.html).

## Testing

[Travis](https://travis-ci.org/sphinx-doc/sphinx)用于Linux上的单元测试和样式检查,
[AppVeyor](https://ci.appveyor.com/project/sphinxdoc/sphinx)适用于Windows上的单元测试,
[CircleCI](https://circleci.com/gh/sphinx-doc/sphinx)适用于类似`TeX编译`的大型任务.

有关在本地运行测试的信息，请参考[开发者指南](http://www.sphinx-doc.org/en/master/devguide.html).

## Contributing

请参考[开发者指南](http://www.sphinx-doc.org/en/master/devguide.html).

## Release signatures

使请用以下密钥对发布进行签名:

- [498D6B9E](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x102C2C17498D6B9E)
- [5EBA0E07](https://pgp.mit.edu/pks/lookup?op=vindex&search=0x1425F8CE5EBA0E07)
