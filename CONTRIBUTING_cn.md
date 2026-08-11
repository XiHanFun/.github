[English](CONTRIBUTING.md)

# 如何为项目贡献代码

## 一、准备工作

- 安装 Git，安装时勾选将 Git 所在目录添加到系统环境变量；
- DotNet 项目：安装 Visual Studio 2022，建议安装 CodeMaid 扩展插件自动格式化代码；
- Vue 项目：安装 Visual Studio Code，建议安装 Prettier - Code formatter 扩展插件自动格式化代码。

新增源码文件请添加如下文件头：

```csharp
// Copyright (c) 2021-Present XiHanFun and contributors.
// Licensed under the MIT License. See LICENSE in the project root for license information.
```

## 二、贡献代码

### 1. 新建自己的分支（Fork）

将本项目仓库 fork 到自己的 git 仓库中。

### 2. 克隆（Clone）

将已经 fork 的仓库 clone 到自己的本地 PC。

### 3. 创建本地分支

如果想要在本项目上做自己的开发，最好创建属于自己的项目分支，如果是直接贡献代码，那么可以直接在 dev 分支上进行操作。

### 4. 开发

1. 发现了一个小 Bug 并进行修改。
2. 在打开的 Issues 中选择功能并进行开发。

### 5. 提交（Commit）

向本地仓库提交代码。

这里是 Git 提交信息前缀规则：

| 前缀     | 描述                                                                           | 示例                                               |
| -------- | ------------------------------------------------------------------------------ | -------------------------------------------------- |
| feat     | 新功能增加（feature）                                                          | feat: add user login feature                       |
| fix      | 修复 BUG                                                                       | fix: correct user authentication                   |
| refactor | 代码重构（既不是新增功能，也不是修复 Bug）                                     | refactor: simplify user validation logic           |
| perf     | 性能优化                                                                       | perf(core): optimize virtual DOM diffing algorithm |
| docs     | 文档/注释                                                                      | docs: update API documentation                     |
| chore    | 依赖更新/脚手架配置修改等                                                      | chore: upgrade React to the latest version         |
| revert   | 代码撤销修改                                                                   | revert: revert commit 12345abc                     |
| style    | 代码风格相关无影响运行结果的                                                   | style: format code with prettier                   |
| test     | 测试相关                                                                       | test: add unit tests for login feature             |
| build    | 影响构建系统或外部依赖的更改（例如：gulp，broccoli，npm）                      | build: update webpack config                       |
| ci       | 持续集成的配置文件和脚本的变动（例如：Travis，Circle，BrowserStack，SauceLabs） | ci: update Travis configuration                    |

这种方式便于清晰区分每种提交的目的和用途。

### 6. 保持本地仓库最新

在准备发起 Pull Request 之前，需要同步原仓库最新的代码，记得检查目前的项目是否是最新的版本。

### 7. 推送到远程仓库（Push）

push 到开发者自己的远程仓库中。

### 8. 发起并完成合并请求（Pull Request）

在 git 仓库中选择自己修改了的分支，点击 create pull request 按钮发起 pull request。

## 三、提交代码的一些约定

发起请求成功后，本项目维护人就可以看到你提交的代码。pull request 如果被同意，你的代码就会被合并到仓库中。这样一次 pull request 就成功了。

至此，我们就完成了一次代码贡献的过程。
