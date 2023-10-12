# vscode-config
An attempt to make VIM key bindings work everywhere!

## Introduction
Selecting an ideal IDE can indeed be a significant challenge for every
developer. You can't even find a helpful article for this. Groups are constantly
criticizing each other. If you ask Emacs users, they might say all other text
editors are garbage. If you visit VIM users, they do the same to the others.

I discovered VIM quite late. After getting used to it, I learned that it's a
structure I can't give up as a developer. I can freely navigate through the code
and easily edit any part of it without ever lifting my hand from the keyboard,
without having to make different CTRL or Shift combinations, and without
repeatedly hitting the Delete or Backspace keys.

But there's an issue with VIM as well: having a good configuration is very
challenging and time-consuming. Even if you achieve a good configuration,
updating any plugin can be a nightmare because community plugins are frequently
updated.

In my opinion, VSCode resolves many plugin issues. It's very powerful and
requires almost no setup, thanks to its LSP (Language Server Protocol)
capabilities. With LSP, you can eliminate many of the extra monotonous tasks.
The Remote - SSH extension is especially good. If you have a significant
distance from the server you're connecting to, you can edit files without
experiencing lag.

The only and the biggest issue with VSCode is that memorizing keyboard shortcuts
can be challenging. This can often leave you having to use the mouse.

There is a VSCode Vim extension that allows you to use VIM keyboard commands
with VSCode, but it's not sufficient on its own because the shortcuts you define
won't work if a file is not in focus. Therefore, it's necessary to use VSCode's
own keyboard shortcut definitions conditionally.

This repository aims to achieve that.

## Current Keybindings

### General Keybindings
- <kbd>Tab</kbd>: Go to next open file in tabs
- <kbd>Shift-Tab</kbd>: Go to previous open file in tabs
- <kbd>Space f f</kbd>: Quick Open
- <kbd>Space f e</kbd>: Open & focus Explorer / Close & focus file
- <kbd>Ctrl+h</kbd>: Focus on the pane left
- <kbd>Ctrl+l</kbd>: Focus on the pane Right

### Explorer Keybindings
- <kbd>a</kbd>: Creates new file
- <kbd>d</kbd>: Creates new folder
- <kbd>x</kbd>: Delete file/folder
- <kbd>r</kbd>: Rename file/folder
- <kbd>Enter</kbd>: Open file, Expand folder
