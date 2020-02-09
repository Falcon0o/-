# cl(MSVC)编译器配置
---

以Visual Studio 2019为例

## 下载相关文件

1. 在官网上下载**Visual Studio 2019生成工具**。使用此类生成工具，可以通过**命令行**接口生成 Visual Studio 项目。 支持的项目包括：ASP.NET、Azure、C++ 桌面、ClickOnce、容器、.NET Core、.NET 桌面、Node.js、Office 和 SharePoint、Python、TypeScript、单元测试、UWP、WCF 和 Xamarin。

2. 打开下载好的**visual Studio Installer**，在**Visual Studio 生成工具2019**内的工作负载中选择安装的项目，以下两项为必须安装的项目

    - C++生成工具，默认路径 `C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools`
    - 通用Windows平台生成工具，默认路径 `C:\Program Files (x86)\Windows Kits\`

## 环境变量设置

|环境变量|值
|-|-
|PATH|C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\VC\Tools\MSVC\14.24.28314\bin\Hostx64\x64
|LIB|C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\VC\Tools\MSVC\14.24.28314\lib\x64
|   |C:\Program Files (x86)\Windows Kits\10\Lib\10.0.18362.0\ucrt\x64
|   |C:\Program Files (x86)\Windows Kits\10\Lib\10.0.18362.0\um\x64
| INCLUDE  |C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\VC\Tools\MSVC\14.24.28314\include
|          |C:\Program Files (x86)\Windows Kits\10\Include\10.0.18362.0\ucrt

Tips: 系统在查找用户设置的环境变量下的路径时，不会递归查找

