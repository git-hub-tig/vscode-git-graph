# Git Graph (Fork)

View a Git Graph of your repository, and perform Git actions from the graph.

**This is a fork of the stale [Git Graph](https://github.com/mhutchie/vscode-git-graph) extension, and the source code can be found on [GitHub](https://github.com/git-hub-tig/vscode-git-graph).**

For any issues or advice, you can find the pull requests page [here](https://github.com/git-hub-tig/vscode-git-graph/pulls).
## Resources

*   [Issues](https://github.com/git-hub-tig/vscode-git-graph/issues)
*   [Marketplace](https://marketplace.visualstudio.com/items?itemName=Gxl.git-graph-3)

This version aims to address some of the long-standing issues and to keep up with the latest VSCode updates.


## Why a Fork?

The original Git Graph extension is an excellent tool, but some issues have remained unresolved for a while. This fork was created to:

*   Fix the disappearing context menu in recent VSCode versions.
*   Improve performance and responsiveness.
*   Add new features that enhance the user experience.

## Key Enhancements in This Fork

*   **Bug Fixes**: Various bug fixes and performance improvements have been implemented.
*   **Tag Filtering**: A new dropdown menu allows you to filter the graph by tags.
*   **Performance Improvements**: The extension's activation events have been optimized for faster startup.
*   **Find Widget**: A search widget has been added to quickly find commits.
*   **Commit Message Formatting**: Support for double newlines in commit messages has been added.

## Major Changes Since 1.31.0

*   **Context Menu Fix**: The disappearing context menu issue in recent versions of VSCode has been resolved.
*   **Tag Dropdown Filter**: A new dropdown menu has been added to filter the graph by tags, making it easier to visualize releases and other important points in your repository's history.
*   **Performance Enhancements**: The extension's activation events have been optimized to improve startup performance, so you can get to your graph faster.
*   **Find Widget**: A new find widget has been integrated, allowing you to quickly search for commits by message, author, or hash.
*   **Commit Message Formatting**: Support for double newlines in commit messages has been added, improving the readability of your commit history.

## What's New in Version 1.34.0

This release includes several new features and improvements. For a detailed list of changes, please refer to the [CHANGELOG.md](CHANGELOG.md).

## Features

This fork retains all the features of the original Git Graph extension, including:

*   **Git Graph View**: A rich, interactive graph of your repository's history.
*   **Git Actions**: Perform a wide range of Git actions directly from the graph.
*   **Commit Details**: View detailed information about commits and file changes.
*   **Commit Comparison**: Compare any two commits to see the differences.
*   **Code Review**: Keep track of reviewed files in the Commit Details and Comparison Views.
*   **Branch and Tag Filtering**: Filter the graph by branches and tags.
*   **Find Widget**: Search for commits by message, author, or hash.
*   **Repository Settings**: Configure remotes, issue linking, and pull request creation.
*   **Customization**: A wide range of settings to customize the look and feel of the graph.

## Extension Settings

For a detailed list of all available settings, please refer to the [Extension Settings documentation](https://github.com/git-hub-tig/vscode-git-graph/wiki/Extension-Settings).

## Release Notes

Detailed release notes are available in the [CHANGELOG.md](CHANGELOG.md).

## Acknowledgements

A big thank you to the original author, [mhutchie](https://github.com/mhutchie), for creating this amazing extension.

Some of the icons used in Git Graph are from the following sources:
- [GitHub Octicons](https://octicons.github.com/) ([License](https://github.com/primer/octicons/blob/master/LICENSE))
- [Icons8](https://icons8.com/icon/pack/free-icons/ios11) ([License](https://icons8.com/license))