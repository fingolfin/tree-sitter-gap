tree-sitter-gap
===============

[![Build/test](https://github.com/fingolfin/tree-sitter-gap/actions/workflows/ci.yml/badge.svg)](https://github.com/fingolfin/tree-sitter-gap/actions/workflows/ci.yml)

GAP grammar for [tree-sitter](https://github.com/tree-sitter/tree-sitter).

Want to help complete this?
- Install tree-sitter
  - on macOS: `brew install tree-sitter`
  - [official instructions](https://tree-sitter.github.io/tree-sitter/creating-parsers#installation)
- [How to create a parser](https://tree-sitter.github.io/tree-sitter/creating-parsers)
- the primary file to edit is `grammar.js`, secondary are the tests inside `corpus`,
  lastly the files inside `examples`; almost everything else is generated by
  `tree-sitter generate`
- Make the existing tests pass
- resolve the TODOs in `grammar.js`
- add more missing language features
- validate by running on the whole GAP library and on packages
