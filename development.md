# How to build and publish the extension


## VSCode
```bash
npm install -g @vscode/vsce

# create vsix
vsce package

# publish solrike.eclipse-theme-by-solrike
vsce publish
```

## Theia

```bash
npm i -g ovsx

npx ovsx create-namespace solrike -p <token>

# publish
npx ovsx publish -p <token>

 ```



## Notes

project - project
source folder - file-submodule
java package - symbol-package (symbol-namespace?)
java class - symbol-class
java interface - symbol-interface
dependency container, like JRE system libs - folder-library
  jar inside dependency container - file-submodule


https://microsoft.github.io/vscode-codicons/dist/codicon.html