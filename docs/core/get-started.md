---
title: Get started with .NET Core
description: Find resources to learn how to build .NET Core applications on Windows, Linux and macOS.
author: johalex
ms.author: johalex
ms.date: 09/14/2017
---

# Get started with .NET Core

This article provides information on getting started with .NET Core. .NET Core can be installed on Windows, Linux, and macOS. You can code in your favorite text editor while your code produces cross-platform libraries and applications. 

If you're unsure what .NET Core is, or how it relates to other .NET technologies, start with the [.NET Core Guide](./). Put simply, .NET Core is an open-source, cross-platform, implementation of .NET.

# [Windows](#tab/windows)

This article demonstrates how to quickly create a .NET Core app from the command line. You can also use [Visual Studio 2017](tutorials/with-visual-studio.md) or [Visual Studio Code](tutorials/with-visual-studio-code.md) to create .NET Core app.

First, download and install the latest [.NET Core SDK](https://www.microsoft.com/net/download/windows) to get started.

Next, open a command prompt such as **PowerShell** or **cmd.exe**, and create a folder and enter it.

```console
mkdir samplecode
cd samplecode
```

Use the `dotnet` command to create, build, and run, an application.

```console
dotnet new console --language c# --output sample1
dotnet build sample1
dotnet run --project sample1
```

After you run the project, you'll see the following output:

```console
Hello World!
```

Congratulations! You've created a simple .NET Core application. This application can be copied and run on any other supported operating system.

# [Linux](#tab/linux)

This article demonstrates how to quickly create a .NET Core app from the command line. You can also use [Visual Studio Code](tutorials/with-visual-studio-code.md) to create .NET Core app.

First, download and install the latest [.NET Core SDK](https://www.microsoft.com/net/download/linux) to get started.

Next, open a command prompt such as **bash** and create a folder and enter it.

```bash
mkdir samplecode
cd samplecode
```

Use the `dotnet` command to create, build, and run, an application.

```bash
dotnet new console --language c# --output sample1
dotnet build sample1
dotnet run --project sample1
```

After you run the project, you'll see the following output:

```console
Hello World!
```

Congratulations! You've created a simple .NET Core application. This application can be copied and run on any other supported operating system.

# [macOS / OS X](#tab/mac)

This article demonstrates how to quickly create a .NET Core app from the command line. You can also use [Visual Studio Code](tutorials/with-visual-studio-code.md) to create .NET Core app.

First, download and install the latest [.NET Core SDK](https://www.microsoft.com/net/download/macos) to get started. .NET Core is supported on OS X El Capitan (version 10.11) and macOS Sierra (version 10.12).

Next, open a command prompt such as **bash** and create a folder and enter it.

```bash
mkdir samplecode
cd samplecode
```

Use the `dotnet` command to create, build, and run, an application.

```bash
dotnet new console --language c# --output sample1
dotnet build sample1
dotnet run --project sample1
```

After you run the project, you'll see the following output:

```console
Hello World!
```

Congratulations! You've created a simple .NET Core application. This application can be copied and run on any other supported operating system.

***

## Tutorials

# [Windows](#tab/windows)

You can get started developing .NET Core apps by following these step-by-step tutorials.

* [Building a C# Hello World Application with .NET Core in Visual Studio 2017](./tutorials/with-visual-studio.md)  
Learn to build, debug, and publish a simple .NET Core console application using C# and Visual Studio 2017.

* [Building a class library with C# and .NET Core in Visual Studio 2017](./tutorials/library-with-visual-studio.md)  
Learn how to build a class library written in C# using Visual Studio 2017.

* [Build a Visual Basic Hello World application with .NET Core in Visual Studio 2017](./tutorials/vb-with-visual-studio.md)  
Learn to build, debug, and publish a simple .NET Core console application using Visual Basic and Visual Studio 2017. 

* [Build a class library with Visual Basic and .NET Core in Visual Studio 2017](./tutorials/vb-library-with-visual-studio.md)  
Learn how to build a class library written in Visual Basic using Visual Studio 2017.


* Get started with Visual Studio Code using C# and .NET Core on Windows

  > [!VIDEO https://channel9.msdn.com/Blogs/dotnet/Get-started-with-VS-Code-using-CSharp-and-NET-Core/player]

  This [Channel9](https://channel9.msdn.com) video shows you how to install and use [Visual Studio Code](https://code.visualstudio.com/), Microsoft's lightweight cross-platform code editor, to create your first console application in .NET Core.

* Get Started with .NET Core and Visual Studio 2017

  > [!VIDEO https://channel9.msdn.com/Blogs/dotnet/Get-Started-NET-Core-Visual-Studio-2017/player]

  This [Channel9](https://channel9.msdn.com) video shows you how to install and use [Visual Studio 2017](https://aka.ms/vsdownload?utm_source=mscom&utm_campaign=msdocs), Microsoft's fully featured IDE, to create your first cross-platform console application in .NET Core.

* [Getting started with .NET Core using the command-line](tutorials/using-with-xplat-cli.md)  
Use any code editor with the [.NET Core cross-platform command-line interface (CLI)](tools/index.md).

See the [Prerequisites for Windows development](windows-prerequisites.md) article for a list of the supported Windows versions.

# [Linux](#tab/linux)

You can get started developing .NET Core apps by following these step-by-step tutorials.

* [Getting started with .NET Core using the command-line](tutorials/using-with-xplat-cli.md)  
Use any code editor with the [.NET Core cross-platform command-line interface (CLI)](tools/index.md).

* [Get started with Visual Studio Code using C# and .NET Core on Ubuntu](https://channel9.msdn.com/Blogs/dotnet/Get-started-with-VS-Code-Csharp-dotnet-Core-Ubuntu)  
This [Channel9](https://channel9.msdn.com) video shows you how to install and use [Visual Studio Code](https://code.visualstudio.com/), Microsoft's lightweight cross-platform code editor, to create your first console application in .NET Core on Ubuntu 14.04.

See the [Prerequisites for Linux development](linux-prerequisites.md) article for a list of the supported Linux distros and versions.

# [macOS / OS X](#tab/mac)

You can get started developing .NET Core apps by following these step-by-step tutorials.

* [Get started with Visual Studio Code using C# and .NET Core on macOS](https://channel9.msdn.com/Blogs/dotnet/Get-started-VSCode-NET-Core-Mac)  
This [Channel9](https://channel9.msdn.com) video shows you how to install and use [Visual Studio Code](https://code.visualstudio.com/), Microsoft's lightweight cross-platform code editor, to create your first console application in .NET Core. 

* [Getting started with .NET Core on macOS, using Visual Studio Code](tutorials/using-on-macos.md)  
A tour of the steps and workflow to create a .NET Core Solution using Visual Studio Code that includes unit tests, third-party libraries and how to use the debugging tools.

* [Getting started with .NET Core using the command-line](tutorials/using-with-xplat-cli.md)  
Use any code editor with the [.NET Core cross-platform command-line interface (CLI)](tools/index.md).

* [Getting started with .NET Core on macOS using Visual Studio for Mac](tutorials/using-on-mac-vs.md)  
This tutorial shows you how to build a simple .NET Core console application using Visual Studio for Mac.

* [Building a complete .NET Core solution on macOS using Visual Studio for Mac](tutorials/using-on-mac-vs-full-solution.md)  
This tutorial shows you how to build a complete .NET Core solution that includes a reusable library and unit testing.

See the [Prerequisites for macOS development](macos-prerequisites.md) article for a list of the supported OS X / macOS versions.

***