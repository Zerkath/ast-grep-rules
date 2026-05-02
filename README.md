# AST Grep rules

Intention is to provide a quick way to scan repositories for anti-patterns that are commonly observed.

Adding new rules can be done with the help of LLMs by giving a sample of the code in question.

[ast-grep] is a better solution than asking LLMs to go through to find these patterns.

## Installation

Install [ast-grep]

```bash
git clone <repo> ~/.config/ast-grep)
```

## Usage

```bash
ast-grep scan -c ~/.config/ast-grep/sgconfig.yml
```

[ast-grep]: https://ast-grep.github.io/guide/quick-start.html
