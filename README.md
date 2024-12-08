# Git Clean

This repository stores some notes on the usage of Git clean.

## Table of Summary

Command	| Description
---|---
`git clean -f`	| Remove untracked files only.
`git clean -fd`	| Remove untracked files and directories.
`git clean -n`	| Show what would be removed without deleting.
`git clean -nd`	| Show untracked files and directories to be removed.
`git clean -fx`	| Remove untracked and ignored files.
`git clean -fdx`	| Remove untracked and ignored files/directories.

Examples

```bash
git clean -fx path/to/clean/dir
```
