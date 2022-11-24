# My cheatsheets

- [Ir a WIKI A](wiki/a)
  - [Ir a WIKI A2](https://github.com/jesuserro/cheatsheets/wiki/a)
  - [Ir a WIKI A3](https://github.com/jesuserro/cheatsheets/tree/master/wiki/a)
  - [Ir a WIKI A4](https://github.com/jesuserro/cheatsheets/master/wiki/a)
- [Ir a WIKI C](wiki/c)
  - [Ir a WIKI C2](https://github.com/jesuserro/cheatsheets/wiki/c)

This repository contains community-sourced cheatsheets to be used with cheat and similar applications.

Format
Cheatsheets are plain-text files that begin with an optional "front matter" header in YAML format. The header may be used to assign "tags" to a sheet, and to specify the sheet's syntax (bash, python, go, etc).

When possible, cheatsheets should conform to this format:

---
syntax: bash
tags: [ vcs, development ]
---
# To stage all changes in the current directory:
git add --all

# To commit staged changes:
git commit -m <message>
As a guideline, it is preferred to use docopt syntax when specifying parameter placeholders. In edge-cases where that syntax may cause confusion, it is permissible to use placeholder values (foo.txt, example.com, etc.) as necessary.

License
Cheatsheets are licensed under Creative Commons CC0 1.0. See LICENSE.txt for the full license text.