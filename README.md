# Eclipse theme by Solrike

Eclipse inspired themes for [VSCode](https://code.visualstudio.com "VSCode")  and [Eclipse Theia IDE](https://theia-ide.org "Theia")



It uses "semantic highlighting" which means that some syntax colouring is done by the language server which can lead to delays in processing of the files.

Languages supported:
* Java (uses "semantic highlighting")
* JavaScript/TypeScript (uses "semantic highlighting")
* Groovy
* CSS


## Install

Search for "Eclipse theme by Solrike" and then install.

The follwing themes get installed:
* Eclipse Light by Solrike
* Eclipse File Icons by Solrike
* Eclipse Product Icons by Solrike

You can also get it from [Visual studio marketplace](https://marketplace.visualstudio.com/items?itemName=solrike.eclipse-theme-by-solrike "marketplace")
or from [Open VSX Registry](https://open-vsx.org/extension/solrike/eclipse-theme-by-solrike "Open VSX Registry")

## Sample from VSCode

<details>
<summary>Themes sample</summary>
  <img src="https://raw.githubusercontent.com/Lucas3oo/eclipse-theme-by-solrike/main/assets/vscode-screenshot.png" name="screenshot">
</details>


## Known issues

Theia Blueprint (1.37.0) do have settings for "semantic highlighting" but it doesn't seems to work, [see](https://github.com/eclipse-theia/theia/issues/10428). Most notably is the fact that class members will not have the correct colour.

```json
"editor.semanticHighlighting.enabled": true
```

Theia Blueprint (1.37.0) doesn't support "product icon themes".


## Other setups

For Eclipse key bindings use for instance: [VSCode Eclipse Keymap](https://marketplace.visualstudio.com/items?itemName=alphabotsec.vscode-eclipse-keybindings "Eclipse Keymap"),
[Theia Eclipse Keymap](https://open-vsx.org/extension/alphabotsec/vscode-eclipse-keybindings "Eclipse Keymap")

For nice a Java project view with Gradle builds install:
* [Project Manager for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-dependency)
* [Gradle for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-gradle)

The Gradle plugin has to be downloaded and installed manually in Theia.

Eclipse editor font is 'Menlo' and line height should be set to 1.25.

```json
"editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace"
"editor.lineHeight": 1.25
```

## Change log
See [CHANGELOG.md](./CHANGELOG.md)


