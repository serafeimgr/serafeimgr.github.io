---
layout: post
title: Favorite VS Code extensions
published: true
---

On this post i am going to list my favorite extensions for [Visual Studio Code](https://code.visualstudio.com/)

These extensions below help me to be more productive on my role as a DevOps Engineer


 - [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

    The most helpful feature of GitLens is that it visualizes code authorship via Git blame annotations.

 - [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)

    Vim emulation for Visual Studio Code.
    Some of my favorite settings that complements vim emulation

    Enable them by adding the following in `settings.json`

    `"editor.lineNumbers": "relative",
    "vim.useSystemClipboard": true`

    This allows the extension to use the system clipboard and also it renders the relative line numbers so i can easily browse a file inside vscode

 - [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)

    Integrates [ShellCheck](https://www.shellcheck.net/) into Visual Studio Code.
    You need to have shellcheck installed on your system

 - [Bash IDE](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode)

    A language server for Bash.

    It exposed IDE-like features for bash/shell scripts into vscode.
    Symbols are added so jump to declaration and references are supported

 - [YAML by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

    YAML Language Support by Red Hat, with built-in [Kubernetes](https://kubernetes.io) syntax support

 - [HashiCorp Terraform](https://marketplace.visualstudio.com/items?itemName=HashiCorp.terraform)

    The HashiCorp Terraform Visual Studio Code extension adds syntax highlighting and other editing features for Terraform files using the Terraform Language Server.

 - [Bracket Pair Colorizer](https://code.visualstudio.com/blogs/2021/09/29/bracket-pair-colorization)

    This functionality used to be included by [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) extension but recently became native to VS Code.

    Enable it by adding the setting

    `"editor.bracketPairColorization.enabled": true`
