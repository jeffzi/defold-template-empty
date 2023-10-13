# Welcome to Defold

This project was created from the "empty" project template.

The settings in ["game.project"](defold://open?path=/game.project) are all the default. A bootstrap empty ["main.collection"](defold://open?path=/main/main.collection) is included.

Check out [the documentation pages](https://defold.com/learn) for examples, tutorials, manuals and API docs.

If you run into trouble, help is available in [our forum](https://forum.defold.com).

Happy Defolding!

## Setup Pre-commit

A framework for managing and maintaining [git pre-commit hooks](https://www.atlassian.com/git/tutorials/git-hooks).
We use pre-commit to run linters on commit, push and in the CI.

1. Install [pre-commit](https://pre-commit.com/#installation)
2. Install [Nodejs](https://nodejs.org/en/) if not already installed.
3. Install [commit-lint](https://commitlint.js.org/):

```bash
npm install -g @commitlint/cli @commitlint/config-conventional
```

3. Set up pre-commit, from repo's directory:

```bash
pre-commit install
pre-commit install --hook-type commit-msg
```

4. Test running hooks:

```bash
pre-commit run -a
```
