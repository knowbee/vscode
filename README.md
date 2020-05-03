# vscode

Keeping track of vs-code extensions

## Get installed extensions

```
   code --list-extensions | xargs -L 1 echo code --install-extension > vscode-extensions.txt
```

### Install from txt file

```
  while read line;do code --install-extension "$line";done <vscode-extensions.txt

```
