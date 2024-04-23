# prg-highlighter README

This is the README for your extension "prg-highlighter". After writing up a brief description, we recommend including the following sections.

## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: Enable/disable this extension.
* `myExtension.thing`: Set to `blah` to do something.

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

---

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**

```json
		"entitys":{
			"patterns": [
			{
				"name": "entity.other.inherited-class.prg",
				"match": "#e5c07b 明黄"
			},
			{
				"name": "entity.other.attribute-name.prg",
				"match": "#d19a66 暗黄"
			},
			{
				"name": "entity.name.function.prg",
				"match": "#61afef 天蓝"
			},
			{
				"name": "entity.name.type.prg",
				"match": "#e5c07b 明黄"
			},
			{
				"name": "entity.name.tag.prg",
				"match": "#e06c75 红"
			},
			{
				"name": "entity.name.section.prg",
				"match": "#61afef 天蓝"
			}
		]

		},
		"variables":{
			"patterns": [{
				"name": "variable.parameter.function.prg",
				"match": "#abb2bf 灰色"
			},
			{
				"name": "variable.language.prg",
				"match": "#e5c07b 明黄"
			},
			{
				"name": "variable.other.prg",
				"match": ""
			}
		]

		},
		"strings":{
			"patterns": [{
				"name": "string.qouted.double.prg",
				"match": "\".*\""
			}]

		},
        "constant":{
			"patterns": [{
				"name": "constant.numeric.prg",
				"match": "#d19a66 暗黄"
			}]

        }
	}

```
