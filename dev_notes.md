# Dump extension list

```bash
# show list
code --list-extensions

# format for installing somewhere else
code --list-extensions | xargs -L 1 echo code --install-extension
```

# Publish extension

Get token from <https://dev.azure.com/Soulsbros>

```bash
# setup
npm install -g @vscode/vsce

# publish new version
vsce package

vsce publish

git commit ...
```
