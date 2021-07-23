# Formatter for eex/leex README

Formatter for Elixir eex/leex html templates. It utilizes htmlbeautifier fork - htmlformatter.

`htmlformatter` needs language settings to be set in the environment to handle utf-8 charsets - like umlauts.
On Macs the LC_* environment variables are not set by default. This extension will set them to `en_US.UTF-8`
if not set.

## Features

* Formats eex / leex files without saving or producing tmp files.

[Demo GIF](https://raw.githubusercontent.com/kelostrada/vscode-html-eex-leex-formatter/main/images/demo.gif)

## Cheers to

Many parts of this software are copied from other projects. Most of all:
* https://github.com/ouven/vscode-yab-for-eex-leex
* https://github.com/golang/vscode-go
* https://github.com/RoyalMist/vscode-eex-format

## Requirements

You have to install `htmlformatter` gem which handles Embedded Elixir:

```
$ sudo gem install htmlformatter
```

## Extension Settings

## Settings

| Setting                              | Description                                           | Default |
| ------------------------------------ | ----------------------------------------------------- | ------- |
| `vscode-html-eex-leex-formatter.tabStops`       | Set number of spaces per indent                       | 2       |
| `vscode-html-eex-leex-formatter.tab`            | Indent using tabs                                     | false   |
| `vscode-html-eex-leex-formatter.indentBy`       | Indent the output by NUMBER steps                     | 0       |
| `vscode-html-eex-leex-formatter.stopOnErrors`   | Stop when invalid nesting is encountered in the input | false   |
| `vscode-html-eex-leex-formatter.keepBlankLines` | Set number of consecutive blank lines                 | 1       |

