<div align="center">

<img src="https://raw.githubusercontent.com/XiHanFun/.github/main/assets/banner_cn.png" alt="曦寒懿" />

<h1>曦寒懿 XiHanFun</h1>

<p><b>构建企业级 .NET + TS 开源生态</b></p>

<p><a href="https://github.com/XiHanFun/.github/blob/main/profile/README.md">English</a> | <b>简体中文</b></p>

<p>
  <a href="https://www.xihanfun.com"><img alt="生态官网" src="https://img.shields.io/badge/%E7%94%9F%E6%80%81%E5%AE%98%E7%BD%91-www.xihanfun.com-7c3aed?style=for-the-badge" /></a>
  <a href="https://docs.xihanfun.com"><img alt="生态文档" src="https://img.shields.io/badge/%E7%94%9F%E6%80%81%E6%96%87%E6%A1%A3-docs.xihanfun.com-2496ED?style=for-the-badge" /></a>
</p>

<p>
  <a href="https://basicapp.xihanfun.com"><img alt="在线体验" src="https://img.shields.io/badge/%E5%9C%A8%E7%BA%BF%E4%BD%93%E9%AA%8C-basicapp.xihanfun.com-0f766e?style=flat-square" /></a>
  <a href="https://qm.qq.com/q/qYp1Urv3z2"><img alt="QQ 群" src="https://img.shields.io/badge/QQ_%E7%BE%A4-462371834-EB1923?style=flat-square&logo=tencentqq&logoColor=white" /></a>
</p>

</div>

主推产品是后端基座 XiHan.Framework、前端基座 XiHan.UI 与基础应用 XiHan.BasicApp，各自独立发布，组合起来就是一套开箱即用的中后台；打印、流程、表单、报表等设计器作为生态产品，可以嵌进任何前端项目。

[生态官网](https://www.xihanfun.com)介绍各产品的定位、能力与版本方案；[生态文档](https://docs.xihanfun.com)提供生态总览、跨仓快速上手与选型指引；每个产品另有自己的文档站。

## 主推产品

后端基座、前端基座与基础应用各管一层，可以单独引用，也能组合成一套完整的中后台。

| 项目 | 简介 |
| :-- | :-- |
| **[XiHan.Framework](https://github.com/XiHanFun/XiHan.Framework)**<br>后端基座<br><a href="https://www.nuget.org/packages?q=XiHan.Framework"><img alt="NuGet" src="https://img.shields.io/nuget/v/XiHan.Framework.Core?style=flat-square&logo=nuget&logoColor=white&label=NuGet&color=004880" /></a> | **快速、轻量、高效、用心的 .NET 开发框架：微内核、能力图谱、管道执行**<br>能力按图谱装配，一份操作契约同时服务 HTTP、gRPC、MCP 与命令行；多租户、工作流、消息与 AI 集成开箱可用，默认实现零外部依赖。<br>[文档站](https://framework.docs.xihanfun.com) |
| **[XiHan.UI](https://github.com/XiHanFun/XiHan.UI)**<br>前端基座<br><a href="https://www.npmjs.com/package/@xihan-ui/vue"><img alt="npm" src="https://img.shields.io/npm/v/@xihan-ui/vue?style=flat-square&logo=npm&logoColor=white&label=npm&color=cb3837" /></a> | **快速、轻量、高效、用心的框架无关 Headless UI 组件库**<br>状态机与无障碍逻辑沉在无头内核，Vue、React 与 Web Components 三套适配器共用同一份行为；基础组件与 AI 组件覆盖从中后台到 AI 对话的界面。<br>[文档站](https://ui.docs.xihanfun.com) |
| **[XiHan.BasicApp](https://github.com/XiHanFun/XiHan.BasicApp)**<br>基础应用<br><a href="https://github.com/XiHanFun/XiHan.BasicApp/releases"><img alt="Release" src="https://img.shields.io/github/v/release/XiHanFun/XiHan.BasicApp?style=flat-square&logo=github&label=Release&color=1f6feb" /></a> | **基于 XiHan.Framework 和 XiHan.UI 的超高颜值通用中后台内核**<br>RBAC + 数据范围 + 字段脱敏的权限体系、多租户隔离、代码生成、实时通信与 AI 能力开箱即用，备好数据库后前后端各一条命令就能跑起来。<br>[文档站](https://basicapp.docs.xihanfun.com) · [在线体验](https://basicapp.xihanfun.com) |

## 生态产品

设计器以原生 Web Components 交付，不绑定前端框架，Vue、React、Angular 或不使用框架的页面都能直接使用。运行时不引入第三方包；模板只是 JSON，数据、存储与权限都经回调交给使用方。

| 项目 | 简介 |
| :-- | :-- |
| **[XiHan.PrintDesigner](https://github.com/XiHanFun/XiHan.PrintDesigner)**<br>打印设计器<br>`@xihan-print/*`<br><a href="https://www.npmjs.com/package/@xihan-print/designer"><img alt="npm" src="https://img.shields.io/npm/v/@xihan-print/designer?style=flat-square&logo=npm&logoColor=white&label=npm&color=cb3837" /></a> | **快速、轻量、高效、用心的框架无关打印设计器**<br>可视化设计打印模板，在浏览器里分页预览与打印；配合本地打印客户端，可以静默直打。<br>[文档站](https://print.docs.xihanfun.com) |
| **[XiHan.FlowDesigner](https://github.com/XiHanFun/XiHan.FlowDesigner)**<br>流程设计器<br>`@xihan-flow/*`<br><a href="https://www.npmjs.com/package/@xihan-flow/designer"><img alt="npm" src="https://img.shields.io/npm/v/@xihan-flow/designer?style=flat-square&logo=npm&logoColor=white&label=npm&color=cb3837" /></a> | **快速、轻量、高效、用心的框架无关流程设计器**<br>可视化编排流程图与审批流，产出与流程引擎无关的流程定义，由使用方对接自己的引擎。<br>[文档站](https://flow.docs.xihanfun.com) |
| **[XiHan.FormDesigner](https://github.com/XiHanFun/XiHan.FormDesigner)**<br>表单设计器<br>`@xihan-form/*`<br><a href="https://www.npmjs.com/package/@xihan-form/designer"><img alt="npm" src="https://img.shields.io/npm/v/@xihan-form/designer?style=flat-square&logo=npm&logoColor=white&label=npm&color=cb3837" /></a> | **快速、轻量、高效、用心的框架无关表单设计器**<br>可视化搭建表单，同一份 JSON 定义既驱动设计器，也驱动业务页面里的表单渲染。<br>[文档站](https://form.docs.xihanfun.com) |
| **[XiHan.ReportDesigner](https://github.com/XiHanFun/XiHan.ReportDesigner)**<br>报表设计器<br>`@xihan-report/*`<br><a href="https://www.npmjs.com/package/@xihan-report/designer"><img alt="npm" src="https://img.shields.io/npm/v/@xihan-report/designer?style=flat-square&logo=npm&logoColor=white&label=npm&color=cb3837" /></a> | **快速、轻量、高效、用心的框架无关报表设计器**<br>可视化设计数据报表与看板，数据由使用方通过回调提供，报表可以导出成 xlsx 工作表。<br>[文档站](https://report.docs.xihanfun.com) |

## 从哪里开始

BasicApp 的后端引用 Framework，前端引用 UI；设计器建立在 UI 之上。可以只取其中一层，也可以从完整的中后台起步。

| 你的场景 | 从这里开始 |
| :-- | :-- |
| 只要后端能力，在现有 ASP.NET Core 项目里按需引用 NuGet 包 | [Framework 快速上手](https://framework.docs.xihanfun.com/quickstart) |
| 只要前端组件，Vue、React 或原生自定义元素任选其一 | [UI 快速上手](https://ui.docs.xihanfun.com/quickstart) |
| 要一套能跑的中后台，在权限、租户与审计之上直接写业务 | [BasicApp 快速开始](https://basicapp.docs.xihanfun.com/getting-started) · [在线体验](https://basicapp.xihanfun.com) |
| 要在自己的页面里嵌打印、流程、表单或报表设计器 | [打印](https://print.docs.xihanfun.com/quickstart) · [流程](https://flow.docs.xihanfun.com/quickstart) · [表单](https://form.docs.xihanfun.com/quickstart) · [报表](https://report.docs.xihanfun.com/quickstart) |
| 还在选型，想先看清各项目的关系 | [生态总览](https://docs.xihanfun.com/cosmos/ecosystem) |

## 参与与交流

- 全部项目以 MIT 许可证开源，开源版完整可用、可以商用。
- 代码在 [GitHub](https://github.com/XiHanFun)（主库）、[Gitee](https://gitee.com/XiHanFun) 与 [GitCode](https://gitcode.com/XiHanFun)（同步备库）三处托管，Issue 与 PR 在哪一处提都收得到。
- 提交代码前请阅读[贡献指南](https://github.com/XiHanFun/.github/blob/main/CONTRIBUTING_cn.md)与[贡献者公约](https://github.com/XiHanFun/.github/blob/main/CODE_OF_CONDUCT_cn.md)。
- QQ 群：[462371834](https://qm.qq.com/q/qYp1Urv3z2) · 邮箱：me@xihanfun.com
