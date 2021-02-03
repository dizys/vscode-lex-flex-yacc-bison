# Lex Flex Yacc Bison

> This is a fork of the original open source VSCode extension [here](https://github.com/faustinoaq/vscode-lex-flex-yacc-bison/) with the intent of making this extension available in [Open VSX Registry](https://open-vsx.org/).

Syntax highlighting for Lex, Flex, Yacc and Bison.

This extension is based on these extensions:

1. [Lex/Flex](https://github.com/LunicLynx/vscode-lex)
2. [Yacc/Bison](https://github.com/SE2Dev/vscode-yacc)

![Example](https://raw.githubusercontent.com/faustinoaq/vscode-lex-flex-yacc-bison/master/images/example.png)

## Overview

A compiler or interpreter for a programming language is often decomposed into two parts:

1. Read the source program and discover its structure.
2. Process this structure, e.g. to generate the target program.

`Lex` and `Yacc` can generate program fragments that solve the first task.

The task of discovering the source structure again is decomposed into subtasks:

1. Split the source file into tokens (Lex).
2. Find the hierarchical structure of the program (Yacc).

Read more in [Lex & Yacc Page](http://dinosaur.compilertools.net/)

## Known Issues

Some keywords aren't detected.

## Release Notes

See [Change Log](https://github.com/faustinoaq/vscode-lex-flex-yacc-bison/blob/master/CHANGELOG.md).

## Contributing

1. Fork it https://github.com/faustinoaq/vscode-lex-flex-yacc-bison/fork
2. Create your feature branch `git checkout -b my-new-feature`
3. Commit your changes `git commit -am 'Add some feature'`
4. Push to the branch `git push origin my-new-feature`
5. Create a new Pull Request

## Contributors

- [@faustinoaq](https://github.com/faustinoaq) Faustino Aguilar - creator, maintainer