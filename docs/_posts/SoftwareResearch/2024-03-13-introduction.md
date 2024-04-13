---
title: "Software Research Introduction"
permalink: /SoftwareResearch/Introduction
date: 2024-03-13 18:44:51 +0800
category: SoftwareResearch
tags:
header:
  teaser: https://upload.wikimedia.org/wikipedia/commons/1/14/Window_%28windowing_system%29.svg
---

This is the introduction to the series articles "Software Research". This series introduces basic information about the software that I am concerned about.

## Main Categories of "Software"

This series mainly introduces application software. Application software refers to software that is used directly by people to fulfill a certain need. Operating systems and hardware drivers are not included.

Network services are not application software. The gray area here is the use of network services. Some software act as a network service client. The following provisions are made here:

* Client software dedicated to a certain commercial network service is regarded as an accessory to the network service and is not regarded as an application software.
* Software that is not targeted at a specific network service provider, but serves as a client for a type of network service protocol, is an application software (such as an e-mail client).

## Extensions and Libraries

For frequently used software, if it has extendsions, the extended software should also be researched and managed. Create a folder with the same name for the software and record the posts about extensions in it.

If the extendsions of multiple software are universal, this should be stated in the descriptions of these software, and the extendsions library of one software should be designated as priority. Generally speaking, extendsions supported by several mutually compatible software are recorded only once.

In addition, relatively fixed and systematic configurations or settings can also be counted as extendsions. For program development environments, all libraries count as extensions. When the programming language runtime environment and the package manager in the development environment are not the same software, all libraries are recorded under the package manager.

In fact, the application softwares themselves are also regarded as extensions of the operating system. What manages them is the system's package management software.

## About Package Dependency

Software that is not used directly used by human and is simply a dependency of other software is generally not recorded. So as the runtime environments of some languages. These softwares should be automatically installed and managed by package management software. If necessary, mention the need to install them in the introductions of the relevant application softwares.

But the libraries called in the programming environment need to be recorded. Because calling them is equivalent to using them directly.

## Symbols and Tags

Here are descriptions of the symbols I'll use in the articles:

* Openness
  * Open Source?
    * 📖 Open Source
    * 📕 Close Source
  * Charge?
    * 🆓 Free
    * 💰 Charge
* System
  * Developer System
    * 🪟 Windows
    * 🍎 MacOS
    * 🐧 Linux-bsed
    * 😈 BSD-based
  * Consumer System
    * 🍏 Apple consumer systems (iOS, iPadOS etc.)
    * 🤖 Android-based consumer systems

Here are some tags I would label these articles:

* Basic Interface
  * CLI: Command Line Interface. Mainly interact with text commands. Can be run in a virtual terminal, but may also be run in other ways such as voice interaction. After all, text commands are abstract and can be used in various carrier.
  * TUI: Text-based User Interface. An interface with a graphical layout rendered in a terminal.
  * GUI: Graphical User Interface. A true flat graphical interface, with keyboard and pointing device as the main control method.
  * TouchGUI: Graphical User Interface. Finger touch is the main mode of operation.

In addition, I will add at least one tag describing the functional positioning of each software. The number of such tags is variable.

## Recommendations

### System Compositions

Currently this category mainly includes package managers and GUI environments.

* 🆓📖-🪟 [WinGet](/softwareresearch/2024/03/27/winget): Windows application softwares manager.

### Mainstream Applications

* 🆓📖-🪟🍎🐧 [7-Zip](/softwareresearch/2024/04/10/7-zip): Archive compression software.
* 🆓📖-🪟🍎🐧😈 [Alacritty](/softwareresearch/2024/03/27/alacritty):  Terminal emulator.
* 🆓📖-🪟🍎🐧 [Git](/softwareresearch/2024/04/09/git): Distributed version control system.
* 🆓📖-🪟🍎🐧 [Git Large File Storage](/softwareresearch/2024/04/09/git-lfs): Git large file management expansion.
* 🆓📖-🪟: [ImageGlass](/softwareresearch/2024/04/09/imageglass): Image viewer and gallery browser.
* 🆓📖-🪟🍎🐧 [MiKTeX](/softwareresearch/2024/04/08/miktex): Typesetting tool set for TeX ecosystem.
* 🆓📖-🪟🍎🐧 [Neovim](/softwareresearch/2024/04/07/neovim): TUI text editor and text editing kernel.
* 🆓📖-🪟🍎🐧 [OhMyPosh](/softwareresearch/2024/03/15/oh-my-posh): Shell display effect configuration tool.
* 🆓📖-🪟🍎🐧 [PowerShell](/softwareresearch/2024/03/15/powershell): Command line shell. Used both in daily operating and scripting.
* 🆓📖-🪟: [Sumatra PDF](/softwareresearch/2024/04/09/sumatra-pdf): Document viewer.
* 🆓📖-🪟🍎🐧 [Visual Studio Code](/softwareresearch/2024/04/07/vs-code): GUI text editor and development environment front-end framework.
  * 🆓📖 [Insert Date String](/softwareresearch/visualstudiocode/2024/04/11/insert-date-string): Insert format date string.
  * 💰📕 [GitHub Copilot](/softwareresearch/visualstudiocode/2024/04/11/github-copilot): GitHub Copilot plugin.
  * 💰📕 [GitHub Copilot Chat](/softwareresearch/visualstudiocode/2024/04/11/github-copilot-chat): GitHub Copilot chat box plugin.
  * 🆓📖 [LaTeX Workshop](/softwareresearch/visualstudiocode/2024/04/08/latex-workshop): Front-end plugin for TeX-based typesetting softwares.
  * 🆓📖 [Markdown All in One](/softwareresearch/visualstudiocode/2024/04/12/markdown-all-in-one): Shortcuts, auto-completion, table formatting etc. for Markdown editing.
  * 🆓📖 [Markdown Extended](/softwareresearch/visualstudiocode/2024/04/12/markdown-extended): More extended syntax for Markdown.
  * 🆓📖 [Markdown Language Basics](/softwareresearch/visualstudiocode/2024/04/12/vscode-markdown): Markdown syntax support.
  * 🆓📖 [Markdown Language Features](/softwareresearch/visualstudiocode/2024/04/12/vscode-markdown-features): Markdown preview.
  * 🆓📖 [Markdown Math](/softwareresearch/visualstudiocode/2024/04/12/vscode-markdown-math): Math extension to Markdown preview.
  * 🆓📖 [Markdown Preview Mermaid Support](/softwareresearch/visualstudiocode/2024/04/12/markdown-preview-mermaid): Preview for Mermaid embedded in Markdown.
  * 🆓📖 [Markdownlint](/softwareresearch/visualstudiocode/2024/04/12/markdownlint): Linter for Markdown.
  * 🆓📖 [Mermaid Markdown Syntax Highlighting](/softwareresearch/visualstudiocode/2024/04/12/mermaid-markdown-syntax): Syntax highlighting for Mermaid embedded in Markdown.
  * 🆓📖 [Material Icon Theme](/softwareresearch/visualstudiocode/2024/04/12/material-icon): File icon theme.
  * 🆓📖 [Material Product Icons](/softwareresearch/visualstudiocode/2024/04/12/material-product): UI icon theme.
  * 🆓📖 [One Dark Darker](/softwareresearch/visualstudiocode/2024/04/12/one-dark-darker): A color theme.

### Alternative Applications

* 🆓📖-🪟🐧 [Nomacs](/softwareresearch/2024/04/09/nomacs): Image viewer, not support APNG for now.
* 💰📕-🪟🍎🐧 [Typora](/softwareresearch/2024/04/14/typora): Markdown viewer and editor.
* 🆓📖-🪟 [Windows Terminal](/softwareresearch/2024/03/14/windows-terminal): Terminal emulator.

### For Fun

* 🆓📖-🪟🍎🐧😈 [GNU Emacs](/softwareresearch/2024/04/07/emacs): A complex system disguised as a text editor.

## Trend

Trends in software recommendation changes.
