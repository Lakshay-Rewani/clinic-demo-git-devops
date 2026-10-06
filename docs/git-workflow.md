# Git Workflow Documentation

## Project

Clinic Demo Website

## Technology Stack

- HTML
- CSS
- JavaScript

## Branching Strategy

This project follows a simple Git workflow:

feature branch → dev → main

### main

Contains the stable version of the website.

### dev

Contains development work before it is released to main.

### feature branches

Used for individual website improvements and changes.

## Pull Requests

Feature branches are merged into the dev branch using Pull Requests.

After development is completed and tested, dev is merged into main using a Pull Request.

## Git Tags

Git tags are used to identify stable releases.

Example:

1.0.0

## Git Stash

Git stash temporarily stores uncommitted changes so the working directory can be switched to another task without committing unfinished work.

## Merge Conflicts

If two branches modify the same part of a file, Git may report a merge conflict. The conflicting sections must be reviewed and resolved manually before committing the final version.

## .gitignore

The .gitignore file prevents unnecessary files such as environment files, logs, temporary files and IDE-specific files from being tracked.
