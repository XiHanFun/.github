[中文](CONTRIBUTING_cn.md)

# How to Contribute Code to Project

This guide is the default contributing convention shared by the repositories of the XiHanFun organization. Each repository documents its own build and test commands and directory layout in its README; where the two differ, the repository's own instructions win.

The code is hosted on GitHub (primary), Gitee and GitCode (synced mirrors), and issues and pull requests are welcome on any of them.

## I. Prerequisites

- Install Git, and add the Git installation directory to the system environment variables during installation;
- .NET projects: install the .NET SDK the repository requires; Visual Studio, Rider, VS Code or any other editor will do;
- Frontend projects: install Node.js and pnpm; see the repository README for the required versions;
- Format code with the configuration the repository ships (such as EditorConfig and ESLint), rather than personal formatting rules.

Add the following file header to new source files:

```csharp
// Copyright (c) 2021-Present XiHanFun and contributors.
// Licensed under the MIT License. See LICENSE in the project root for license information.
```

```ts
/*
 * Copyright (c) 2021-Present XiHanFun and contributors.
 * Licensed under the MIT License. See LICENSE in the project root for license information.
 */
```

## II. Contributing Code

### 1. Fork the Repository

Fork the project repository to your own Git repository.

### 2. Clone the Repository

Clone the forked repository to your local PC.

### 3. Create a Local Branch

Development happens on the dev branch. Create your own branch from dev and make your changes there.

### 4. Development

1. Find and fix a small bug.
2. Choose a feature to develop in the opened Issues.

Before committing, make sure the repository builds and its tests pass locally; the commands are in the repository README or in the CI workflows under `.github/workflows/`.

### 5. Commit

Commit your changes to your local repository.

Here are the Git commit message prefix rules:

| prefix       | description                                              | example                                       |
| ------------ | -------------------------------------------------------- | --------------------------------------------- |
| **feat**     | New feature                                              | `feat: add login page`                        |
| **fix**      | Bug fix                                                  | `fix: correct the message on failed sign-in`  |
| **refactor** | Code refactoring (neither a feature nor a fix)           | `refactor: simplify user validation logic`    |
| **perf**     | Performance optimization                                 | `perf: avoid repeated work when rendering lists` |
| **docs**     | Documentation or comments                                | `docs: add installation instructions`         |
| **style**    | Formatting changes that do not affect behavior           | `style: unify indentation per EditorConfig`   |
| **test**     | Add or modify tests                                      | `test: add unit tests for the login flow`     |
| **build**    | Changes to the build system or external dependencies     | `build: upgrade dependencies`                 |
| **ci**       | Changes to continuous integration configuration and scripts | `ci: adjust the GitHub Actions workflow`   |
| **chore**    | Other chores that touch neither source nor tests         | `chore: update .gitignore`                    |
| **revert**   | Revert an earlier commit                                 | `revert: revert 12345abc`                     |

This approach makes it easy to clearly distinguish the purpose and use of each commit.

### 6. Keep the Local Repository Up-to-Date

Before submitting a pull request, synchronize the latest code from the dev branch of the original repository.

### 7. Push to Remote Repository

Push the changes to your own remote repository.

### 8. Submit and Complete a Pull Request

Select your modified branch, open a pull request against the dev branch of the original repository, and explain what changed and why; if the repository has a pull request template, fill it in.

## III. Code Submission Conventions

Once the pull request is submitted successfully, the project maintainer will review your code. If the pull request is accepted, your code will be merged into the repository. This completes the process of code contribution.

Please follow the [Contributor Covenant](CODE_OF_CONDUCT.md) while taking part. Thank you for your contribution!
