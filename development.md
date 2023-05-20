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
