[中文](CONTRIBUTING_cn.md)

# How to Contribute Code to Project

## I. Prerequisites

- Install Git;
- Install Sourcetree, a graphical interface for Git;
- Make sure to add the Git installation directory to the system environment variables when installing Git.

<details>
<summary>1. DotNet Project</summary>

To begin with, you should install Visual Studio 2022 and the CodeMaid extension plugin, which can automatically format your code. If you are developing new features, it is highly recommended that you add a file header, as this will be of great benefit when modifying code files later on or working on collaborative projects. Here is an example of what this header could look like:

```csharp
#region <<Copyright and Version>>

// ----------------------------------------------------------------
// Copyright ©2024 ZhaiFanhua All Rights Reserved.
// Licensed under the MIT License. See LICENSE in the project root for license information.
// FileName:ChatHub
// Guid:ee669dee-30c7-4d21-8eb4-f24d8dc0f44c
// Author:zhaifanhua
// Email:me@zhaifanhua.com
// CreatedTime:2024-04-16 上午 03:59:25
// ----------------------------------------------------------------

#endregion <<Copyright and Version>>
```

Now, let's talk about how to create and modify default templates.

#### 1. Creating a New Template File

> Note: The environment I am using is Visual Studio 2022. The following templates are suitable for C#10 new syntax. For old syntax and old versions, similar methods can be used to modify them.

Create the following three files in an empty directory:

Class.cs

```csharp
#region <<Copyright and Version>>

// ----------------------------------------------------------------
// Copyright ©$year$ ZhaiFanhua All Rights Reserved.
// Licensed under the MIT License. See LICENSE in the project root for license information.
// FileName:$safeitemname$
// Guid:$guid1$
// Author:$username$
// Email:me@zhaifanhua.com
// CreateTime:$time$
// ----------------------------------------------------------------

#endregion <<Copyright and Version>>

namespace $rootnamespace$;

/// <summary>
/// $safeitemrootname$
/// </summary>
public class $safeitemrootname$
{
}
```

Controller.cs `Here, only ApiController is used.`

```csharp
#region <<Copyright and Version>>

// ----------------------------------------------------------------
// Copyright ©$year$ ZhaiFanhua All Rights Reserved.
// Licensed under the MIT License. See LICENSE in the project root for license information.
// FileName:$safeitemname$
// Guid:$guid1$
// Author:$username$
// Email:me@zhaifanhua.com
// CreateTime:$time$
// ----------------------------------------------------------------

#endregion <<Copyright and Version>>

using Microsoft.AspNetCore.Http;
using Microsoft.AspNetCore.Mvc;

namespace $rootnamespace$;

/// <summary>
/// $safeitemrootname$
/// </summary>
[Route("api/[controller]")]
[ApiController]
public class $safeitemname$ : ControllerBase
{
}
```

Interface.cs

```csharp
#region <<Copyright and Version>>

// ----------------------------------------------------------------
// Copyright ©$year$ ZhaiFanhua All Rights Reserved.
// Licensed under the MIT License. See LICENSE in the project root for license information.
// FileName:$safeitemname$
// Guid:$guid1$
// Author:$username$
// Email:me@zhaifanhua.com
// CreateTime:$time$
// ----------------------------------------------------------------

#endregion <<Copyright and Version>>

namespace $rootnamespace$;

/// <summary>
/// $safeitemrootname$
/// </summary>
public interface $safeitemrootname$
{
}
```

#### 2. Finding the Template Directory and Copying Files

For example, if you have installed Visual Studio 2022 in the C drive, the corresponding template directory would be:

Class

> C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\ItemTemplates\CSharp\Code\2052\Class
> C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\ItemTemplates\AspNetCore\Code\1033\Class

Interface

> C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\ItemTemplates\CSharp\Code\2052\Interface
> C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\ItemTemplates\AspNetCore\Code\1033\Interface

Controller

> C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\ItemTemplates\AspNetCore\Web\ASP.NET\1033\WebApiEmptyController

</details>

<details>
<summary>2. Vue Project</summary>

Firstly, you should install Visual Studio Code and the Prettier - Code formatter extension plugin, which can automatically format your code.

</details>

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

Commit the bug fix to the local repository.

### 6. Keep the Local Repository Up-to-Date

Before submitting a pull request, synchronize the latest code from the original repository and make sure that your project is up to date.

### 7. Push to Remote Repository

Push the changes to your own remote repository.

### 8. Submit and Complete a Pull Request

Select the modified branch in the Git repository and click the create pull request button to submit the pull request.

## III. Code Submission Conventions

Once the pull request is submitted successfully, the project maintainer will review your code. If the pull request is accepted, your code will be merged into the repository. This completes the process of code contribution.

Thank you for your contribution!
