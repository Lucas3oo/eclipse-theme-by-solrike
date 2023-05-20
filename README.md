# Eclipse theme by Solrike

Eclipse inspired colour theme for VSCode and Theia.

It uses "semantic highlighting" which means that some syntax colouring is done by the language server which can lead to delays in processing of the files.

Languages supported:
* Java (uses "semantic highlighting")
* JavaScript/TypeScript (uses "semantic highlighting")
* Groovy
* CSS


## Install

Search for "Eclipse theme by Solrike" and then install. The theme is called "Eclipse Light by Solrike".


## Sample from VSCode

![altText](https://github.com/Lucas3oo/eclipse-theme-by-solrike/blob/main/assets/vscode-screenshot.png "title")


## Known issues

Theia Blueprint (1.37.0) do have settings for "semantic highlighting" but it doesn't seems to work. Most notably is the fact that class members will not have the correct colour.

    editor.semanticHighlighting.enabled = true

## Other setups

For Eclipse key bindings use for instance: [Eclipse Keymap](https://marketplace.visualstudio.com/items?itemName=alphabotsec.vscode-eclipse-keybindings "Eclipse Keymap")

Eclipse editor font is 'Menlo' and line height should be set to 1.25.

```json
"editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace"
"editor.lineHeight": 1.25
```

## Change log
See [CHANGELOG.md](./CHANGELOG.md)


