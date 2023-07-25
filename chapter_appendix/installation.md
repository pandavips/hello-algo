---
comments: true
---

# 16.1. &nbsp; 编程环境安装

## 16.1.1. &nbsp; VSCode

本书推荐使用开源轻量的 VSCode 作为本地 IDE ，下载并安装 [VSCode](https://code.visualstudio.com/) 。

## 16.1.2. &nbsp; Java 环境

1. 下载并安装 [OpenJDK](https://jdk.java.net/18/)（版本需满足 > JDK 9）。
2. 在 VSCode 的插件市场中搜索 `java` ，安装 Extension Pack for Java 。

## 16.1.3. &nbsp; C/C++ 环境

1. Windows 系统需要安装 [MinGW](https://sourceforge.net/projects/mingw-w64/files/)（[配置教程](https://blog.csdn.net/qq_33698226/article/details/129031241)），MacOS 自带 Clang 无需安装。
2. 在 VSCode 的插件市场中搜索 `c++` ，安装 C/C++ Extension Pack 。
3. （可选）打开 Settings 页面，搜索 `Clang_format_fallback Style` 代码格式化选项，设置为 `{ BasedOnStyle: Microsoft, BreakBeforeBraces: Attach }` 。

## 16.1.4. &nbsp; Python 环境

1. 下载并安装 [Miniconda3](https://docs.conda.io/en/latest/miniconda.html) 。
2. 在 VSCode 的插件市场中搜索 `python` ，安装 Python Extension Pack 。
3. （可选）在命令行输入 `pip install black` ，安装代码格式化工具。

## 16.1.5. &nbsp; Go 环境

1. 下载并安装 [go](https://go.dev/dl/) 。
2. 在 VSCode 的插件市场中搜索 `go` ，安装 Go 。
3. 快捷键 `Ctrl + Shift + P` 呼出命令栏，输入 go ，选择 `Go: Install/Update Tools` ，全部勾选并安装即可。

## 16.1.6. &nbsp; JavaScript 环境

1. 下载并安装 [node.js](https://nodejs.org/en/) 。
2. 在 VSCode 的插件市场中搜索 `javascript` ，安装 JavaScript (ES6) code snippets 。
3. （可选）在 VSCode 的插件市场中搜索 `Prettier` ，安装代码格式化工具。

## 16.1.7. &nbsp; C# 环境

1. 下载并安装 [.Net 6.0](https://dotnet.microsoft.com/en-us/download) ；
2. 在 VSCode 的插件市场中搜索 `c#` ，安装 c# 。

## 16.1.8. &nbsp; Swift 环境

1. 下载并安装 [Swift](https://www.swift.org/download/)；
2. 在 VSCode 的插件市场中搜索 `swift` ，安装 [Swift for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=sswg.swift-lang)。

## 16.1.9. &nbsp; Rust 环境

1. 下载并安装 [Rust](https://www.rust-lang.org/tools/install)；
2. 在 VSCode 的插件市场中搜索 `rust` ，安装 [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)。