# `gh clear` GitHub CLI Extension
[GitHub CLI](https://github.com/cli/cli) extension to switch back to the default branch and delete the current branch locally, if there are no uncommitted changes.

## Instalation
```
gh extension install jjocenio/gh-clear
``` 

## Usage
```
gh clear [<default-branch-name>]
```

If you are in a detached head branch, you need to specify the default branch name because it can't be detected.

