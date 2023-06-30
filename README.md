# 欢迎来到 Win32 应用隔离存储库

Win32 应用隔离是 Windows 上的一项新安全功能，它有助于在应用程序受到威胁时限制损害并保护用户隐私选择。
Win32 应用隔离建立在 [AppContainers](https://learn.microsoft.com/en-us/windows/win32/secauthz/implementing-an-appcontainer) 的基础上，它提供了一个安全边界，以及虚拟化资源并提供对其他资源的代理访问的组件。
此存储库包含了帮助您隔离应用程序的文档和工具。

## 入门指南

* 隔离您的应用程序的第一步是按照[此处](docs/packaging/msix-packaging-tool.md)的说明将其打包以运行隔离。
* 一旦您打包好了应用程序，使用[应用程序能力分析器](docs/profiler/application-capability-profiler.md)来更新应用程序，以授予其访问其他资源的权限。
* 我们还有关于[基础知识](docs/fundamentals)的其他文档，包括文件访问同意。
* 现在，您已经准备好在 Windows 上部署和运行您的应用程序了。

用于打包应用程序以运行隔离的工具的二进制文件在存储库的[发布](https://github.com/microsoft/win32-app-isolation/releases)部分中共享。

支持的 Windows 构建和工具的发布说明可以在[此处](relnotes/windows-release-notes.md)找到。

## 与团队沟通

我们很乐意听取您的反馈并回答您的问题！
与团队沟通的最佳方式是通过 GitHub 的[讨论](https://github.com/microsoft/win32-app-isolation/discussions)和[问题](https://github.com/microsoft/win32-app-isolation/issues)。
在创建新的讨论和问题之前，请先搜索是否有类似的讨论和问题。

## 资源

您可以使用以下资源找到有关 Win32 应用隔离的其他信息：

* [Win32 应用隔离 Build 会话](https://www.youtube.com/watch?v=w6VwHGPz12w&pp=ygUTd2luMzIgYXBwIGlzb2xhdGlvbg%3D%3D&ab_channel=MicrosoftDeveloper)
* [Win32 应用隔离博客](https://blogs.windows.com/windowsdeveloper/2023/06/14/public-preview-improve-win32-app-security-via-app-isolation/)

## 贡献

如果您想为文档做出贡献，请先熟悉下面的行为准则资源，然后提交拉取请求。

本项目采用了[Microsoft 开源行为准则](https://opensource.microsoft.com/codeofconduct/)。
有关更多信息，请参见[行为准则 FAQ](https://opensource.microsoft.com/codeofconduct/faq/)或
通过发送电子邮件至[opencode@microsoft.com](mailto:opencode@microsoft.com)与我们联系以获取更多问题或评论。

## 商标

本项目可能包含项目、产品或服务的商标或标志。Microsoft 商标或标志的授权使用受到并必须遵循[Microsoft 商标和品牌指南](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general)的规定。
在本项目的修改版本中使用 Microsoft 商标或标志不得引起混淆或暗示 Microsoft 赞助。
任何第三方商标或标志的使用均受到该第三方的政策的约束。
