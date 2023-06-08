# Contributing guide lines
To contribute to this project, is essential to follow [Code of Conduct](https://github.com/NicholasPilotto/cleanify/blob/develop/CODE_OF_CONDUCT.md) file.

## Repo structure
The default branch is ```develop```. Here is where developing is situated. In this branch will be merged every ```feature``` branch, meanwhile, the production code is situated in ```main``` branch. This pattern is called [Git flow](https://danielkummer.github.io/git-flow-cheatsheet/).

### Features
Every new feature starts in its ```feature``` branch. When the code is ready (and tested) it will be merged in ```develop``` branch.
When the code is mature, ```release``` branch is created and, after tests, it will be merged into ```main```.

### Hotfixes
```hotfix``` branches save us from bug in production. In facts, when a bug needs to be solved immidiately, we create an ```hotfix``` branch, solve the error and merge it on ```main``` branch.

## Issues
Anyone can create an issue. Issues are used to report bugs, questions and suggest new feature. <br>