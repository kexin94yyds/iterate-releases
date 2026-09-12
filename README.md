# iterate

在 AI 任务中查看阶段结果、补充反馈，再继续推进。

当你需要看一眼 AI 做到了哪里，或者想补充一个条件时，iterate 提供一个交互窗口，让你把反馈交回当前任务。

**[下载 macOS Apple Silicon 版](https://github.com/kexin94yyds/iterate-releases/releases/download/v0.6.5/iterate_aarch64.dmg)** · **[Windows 与版本说明](https://github.com/kexin94yyds/iterate-releases/releases/tag/v0.6.4)** · **[全部版本](https://github.com/kexin94yyds/iterate-releases/releases)**

## 适合怎样的使用场景

你正在让 AI 完成一个任务。它交回阶段结果，你查看后补充意见，AI 收到反馈继续工作。

例如：

1. AI 完成一个小修改，把结果交给你查看。
2. 你在 iterate 中输入补充意见。
3. 反馈回到客户端，AI 接着处理当前任务。

接入指南涵盖 Windsurf、Cursor 和 Codex CLI。其他支持 MCP 的客户端需要按自身配置方式接入。

## 下载与安装

| 系统 | 下载 | 当前说明 |
|---|---|---|
| macOS Apple Silicon | [iterate 0.6.5 DMG](https://github.com/kexin94yyds/iterate-releases/releases/download/v0.6.5/iterate_aarch64.dmg) | 免激活版；安装包已签名并通过 Apple 公证 |
| Windows x64 | [iterate 0.6.4 ZIP](https://github.com/kexin94yyds/iterate-releases/releases/download/v0.6.4/iterate-windows-x64.zip) | 按包内说明安装；macOS 的免激活更新未改变 Windows 激活策略 |

macOS 用户打开 DMG，把 iterate 放入 Applications，再打开应用。

随后将 iterate 接入你正在使用的 AI 客户端。可以下载 [安装助手说明](https://github.com/kexin94yyds/iterate-releases/releases/download/v0.6.5/INSTALLATION.md)，把其中的完整提示词交给客户端中的 AI，并告诉它你的系统和客户端名称。它会按说明协助配置 MCP、刷新客户端并验证连接。

## 第一次使用：完成一次反馈

接入后，可以让 AI 做一个小测试：

> 请调用 iterate 的交互工具，显示一条测试消息，等待我回复；收到后告诉我你收到的内容。

在 iterate 窗口中回复一段简单文字。客户端中的 AI 收到并复述这段文字，说明这次反馈路径已经连通。接下来再把它用于真实任务。

如果没有弹窗、客户端没有发现工具，或者提交后收不到反馈，请继续按安装助手说明排查。

## 遇到问题

请在 [Issues](https://github.com/kexin94yyds/iterate-releases/issues) 说明：

- 使用的系统、iterate 版本和 AI 客户端。
- 做到哪一步，原本预期发生什么。
- 实际出现的提示或现象。

附上相关信息即可，请去掉截图和日志中的密钥、账号及私人内容。

## 支持项目

如果 iterate 帮到了你，欢迎 Star 收藏、分享自己的使用方法，或告诉我们你在哪一步遇到了困难。

本仓库提供 iterate 的安装包和版本说明。

