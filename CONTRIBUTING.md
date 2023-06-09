# Contributing guide lines
To contribute to this project, is essential to follow [Code of Conduct](https://github.com/NicholasPilotto/cleanify/blob/develop/CODE_OF_CONDUCT.md) file.

## Repo structure
The default branch is ```develop```. Here is where developing is situated. In this branch will be merged every ```feature``` branch, meanwhile, the production code is situated in ```main``` branch. This pattern is called [Git flow](https://danielkummer.github.io/git-flow-cheatsheet/).

### Features
Every new feature starts in its ```feature``` branch. When the code is ready (and tested) it will be merged in ```develop``` branch.

### Releases
When code is mature, all issues scheduled for current ```milestone``` are closed, ```develop``` branch is fork in a ```release``` branch. In these branches we do not add new features, but only bug fixes. <br>
Once everything is ready, ```release``` branch gets merged into ```main``` and tagged with a version number.

### Fixes
When we are working on a ```release``` branch and we want to solve a bug, we fork a ```fix``` branch starting by ```release``` and merge into it when bug is solved.

### Hotfixes
```hotfix``` branches save us from bug in production. In facts, when a bug needs to be solved immidiately, we create an ```hotfix``` branch, solve the error and merge it on ```main``` branch.

### Naming
Every branch name must starts with its category, followed by the name of the action we want to implement in kebab case, e.g.
```
feature/new-feature-to-add
```