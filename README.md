# Unmicrosofted Code
[![Feature Requests](https://img.shields.io/github/issues/katuak/unmicrosofted-vscode/feature-request.svg)](https://github.com/katuak/unmicrosofted-vscode?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc)
[![Bugs](https://img.shields.io/github/issues/katuak/unmicrosofted-vscode/bug.svg)](https://github.com/katuak/unmicrosofted-vscode/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3Abug)
[![Discord](https://img.shields.io/badge/chat-on%20discord-violet.svg)](https://discord.gg/YGbRtWTkpz)

## The Repository

Welcome to Unmicrosofted Code! This is where I, an unpaid individual with a life (katuak) develop a fork of [Code - OSS](https://github.com/microsoft/vscode) ( which is different from [Microsoft Visual Studio Code](https://github.com/microsoft/vscode/wiki/Differences-between-the-repository-and-Visual-Studio-Code)).

This software contains Code's original [MIT license](https://mit-license.org/), however changes are relicensed under [GNU-GPL2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

**You aren't allowed to release a propietary product based on my free work. You must open source all your changes.**

## Roadmap

- [x] No telemetry
- [x] No mangling (allows for extensions such as [monkey-patch](https://marketplace.visualstudio.com/items?itemName=iocave.monkey-patch) and [customize-ui](https://marketplace.visualstudio.com/items?itemName=iocave.customize-ui))
- [ ] Backend-agnostic configurable extension stores
- [ ] No safe/unsafe contexts / dialogs
- [ ] Block extension's telemetry
- [ ] Permissions API for extensions
- [ ] Allow to set the IDE's font family.

## Unmicrosofted Code

<p align="center">
  <img alt="VS Code in action" src="https://user-images.githubusercontent.com/35271042/118224532-3842c400-b438-11eb-923d-a5f66fa6785a.png">
</p>

[Unmicrosofted Code](https://katuak.github.io/unmicrosofted-vscode) is a distribution of the `Code - OSS` repository with**OUT** Microsoft-specific customizations released under a [GNU GPL 2.0 license](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

[Unmicrosofted Code](https://katuak.github.io/unmicrosofted-vscode) combines the versatility of a [Microsoft VS Code](https://code.visualstudio.com) with the right of the open source community for privacy and customizability.

We intend to make monthly releases, however keep in mind it's not realistical for us to keep up with the rythm of VSCode's development without financiation.

## Contributing

There are many ways in which you can participate in this project, for example:

* [Submit bugs and feature requests](https://github.com/microsoft/vscode/issues), and help us verify as they are checked in
* Review [source code changes](https://github.com/microsoft/vscode/pulls)
* Review the [documentation](https://github.com/microsoft/vscode-docs) and make pull requests for anything from typos to additional and new content

If you are interested in fixing issues and contributing directly to the code base,
please see the document [How to Contribute](https://github.com/microsoft/vscode/wiki/How-to-Contribute), which covers the following:

* [How to build and run from source](https://github.com/microsoft/vscode/wiki/How-to-Contribute)
* [The development workflow, including debugging and running tests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#debugging)
* [Coding guidelines](https://github.com/microsoft/vscode/wiki/Coding-Guidelines)
* [Submitting pull requests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#pull-requests)
* [Finding an issue to work on](https://github.com/microsoft/vscode/wiki/How-to-Contribute#where-to-contribute)
* [Contributing to translations](https://aka.ms/vscodeloc)

## Feedback

* Ask a question on [Stack Overflow](https://stackoverflow.com/questions/tagged/vscode)
* [Request a new feature](CONTRIBUTING.md)
* Upvote [popular feature requests](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc)
* [File an issue](https://github.com/microsoft/vscode/issues)
* Connect with the extension author community on [GitHub Discussions](https://github.com/microsoft/vscode-discussions/discussions) or [Slack](https://aka.ms/vscode-dev-community)
* Follow [@code](https://twitter.com/code) and let us know what you think!

See our [wiki](https://github.com/microsoft/vscode/wiki/Feedback-Channels) for a description of each of these channels and information on some other available community-driven channels.

## Related Projects

Many of the core components and extensions to VS Code live in their own repositories on GitHub. For example, the [node debug adapter](https://github.com/microsoft/vscode-node-debug) and the [mono debug adapter](https://github.com/microsoft/vscode-mono-debug) repositories are separate from each other. For a complete list, please visit the [Related Projects](https://github.com/microsoft/vscode/wiki/Related-Projects) page on our [wiki](https://github.com/microsoft/vscode/wiki).

## Bundled Extensions

VS Code includes a set of built-in extensions located in the [extensions](extensions) folder, including grammars and snippets for many languages. Extensions that provide rich language support (code completion, Go to Definition) for a language have the suffix `language-features`. For example, the `json` extension provides coloring for `JSON` and the `json-language-features` extension provides rich language support for `JSON`.

## Development Container

This repository includes a Visual Studio Code Dev Containers / GitHub Codespaces development container.

- For [Dev Containers](https://aka.ms/vscode-remote/download/containers), use the **Dev Containers: Clone Repository in Container Volume...** command which creates a Docker volume for better disk I/O on macOS and Windows.
     - If you already have VS Code and Docker installed, you can also click [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/microsoft/vscode) to get started. This will cause VS Code to automatically install the Dev Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.
- For Codespaces, install the [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces) extension in VS Code, and use the **Codespaces: Create New Codespace** command.

Docker / the Codespace should have at least **4 Cores and 6 GB of RAM (8 GB recommended)** to run full build. See the [development container README](.devcontainer/README.md) for more information.

## License

Copyright (c) katuak. All rights reserved.

Licensed under the [GNU GPL 2.0](LICENSE.txt) license

## Microsoft VS Code License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE.MIT.txt) license.
