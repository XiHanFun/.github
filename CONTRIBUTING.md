[中文](CONTRIBUTING_cn.md)

# How to Contribute Code to Project

## I. Prerequisites

- Install Git, and add the Git installation directory to the system environment variables during installation;
- DotNet projects: install Visual Studio 2022, and the CodeMaid extension plugin is recommended for automatic code formatting;
- Vue projects: install Visual Studio Code, and the Prettier - Code formatter extension plugin is recommended for automatic code formatting.

Add the following file header to new source files:

```csharp
// Copyright (c) 2021-Present XiHanFun and contributors.
// Licensed under the MIT License. See LICENSE in the project root for license information.
```

## II. Contributing Code

### 1. Fork the Repository

Fork the project repository to your own Git repository.

### 2. Clone the Repository

Clone the forked repository to your local PC.

### 3. Create a Local Branch

If you want to develop your own project based on this project, it is best to create your own project branch. If you are contributing code directly, you can work on the dev branch.

### 4. Development

1. Find and fix a small bug.
2. Choose a feature to develop in the opened Issues.

### 5. Commit

Commit your changes to your local repository.

Here are the Git commit message prefix rules:

| prefix       | description                                                          | example                                              |
| ------------ | -------------------------------------------------------------------- | ---------------------------------------------------- |
| **feat**     | New Feature                                                          | `feat: add login page`                               |
| **fix**      | Bug fixes                                                            | `fix: resolve issue with user authentication`        |
| **docs**     | Document Modifications                                               | `docs: update README with installation instructions` |
| **style**    | Code style (changes that don't affect functionality)                 | `style: format code with Prettier`                   |
| **refactor** | Code refactoring (no features and fixes)                             | `refactor: refactor the authentication module`       |
| **perf**     | Performance optimization                                             | `perf: optimize image loading speed`                 |
| **test**     | Add or modify tests                                                  | `test: add unit tests for login functionality`       |
| **chore**    | Miscellaneous work (build tasks, tool configurations, etc.)          | `chore: update dependencies`                         |
| **ci**       | Continuous integration related modifications                         | `ci: update GitHub Actions workflow`                 |
| **build**    | Build-related changes (affecting the build system or dependencies)   | `build: update webpack config for production build`  |

This approach makes it easy to clearly distinguish the purpose and use of each commit.

### 6. Keep the Local Repository Up-to-Date

Before submitting a pull request, synchronize the latest code from the original repository and make sure that your project is up to date.

### 7. Push to Remote Repository

Push the changes to your own remote repository.

### 8. Submit and Complete a Pull Request

Select the modified branch in the Git repository and click the create pull request button to submit the pull request.

## III. Code Submission Conventions

Once the pull request is submitted successfully, the project maintainer will review your code. If the pull request is accepted, your code will be merged into the repository. This completes the process of code contribution.

Thank you for your contribution!
