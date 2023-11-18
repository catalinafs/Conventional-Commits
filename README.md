# Conventional Commits

Writing good commit messages is important so that your project history is readable, easily scannable, and understandable by anyone participating in the project.

imagen aqui de commit malo

## Basic Syntax

This is the basic syntax of conventional commits:

```
<commit-type>: <commit-description>
```

## Slightly Advanced Syntax

```
<commit-type>[optional scope]: <commit-description>

[optional body]

[optional footer(s)]
```

## Commit Types

- **feat:** Features, used when a new feature is added
- **fix:** Bug Fixes, used when the commit represents the bug fix in your application
- **perf:** Perfor­mance Improv­ements, used when the commit represents the bug fix in your application
- **docs:** Perfor­mance Improv­ements, used when the commit represents the bug fix in your application
- **refactor:** Code Refact­oring, A change in code that does not fix a bug or add a feature but changes names of variables, functions, etc
- **build:** Builds, Changes that affect the build system or external dependencies, for example adding or removing a dependency
- **style:** Styles, Changes in the formatting code, tabs, spaces or semicolons, etc; They do not affect the performance of the code
- **test:** Tests, Adding missing tests or correcting existing tests
- **revert:** Reverts, Reverts a previous commit

## Breaking Changes

```
BREAKING CHANGES: or !
```

Indicates that a change made to the code is a significant break or change that may affect compatibility with earlier versions of the software. Which means that additional actions are required by users or developers to adapt to the new version of the software.

### Example #1

This example uses the slightly advanced syntax of conventional commits

```
feat: agregar nueva funcionalidad de autenticación

BREAKING CHANGE: se ha cambiado el formato de los tokens de autenticación. Los tokens ahora son JWT en lugar de tokens de sesión. Esto requiere que los usuarios actualicen sus implementaciones de autenticación para utilizar el nuevo formato de token.
```

First there is a feat indicating that a new functionality was created, then it indicates that a BREAKING CHANGE was made and a description of the change is given

### Example #2

This example uses the basic syntax of conventional commits

```
BREAKING CHANGE:feat:: agregar nueva funcionalidad de autenticación, cambiando los tokens de sesion por JWT.
```

First there is a feat indicating that a new functionality was created, then it indicates that a BREAKING CHANGE was made and a description of the change is given

## [For more information click here](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines)
