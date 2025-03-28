# Jacobs Dark Theme

One dark theme for Visual Studio Code, loosely based on Atom's One Dark




## Install

press `ctl/command + shift + p` to launch the command palette then run
```
ext install =
```

## Screenshot


## Modification
```
npm install -g @vscode/vsce
vsce package
code --install-extension theme-jacobs-dark-0.1.0.vsix

code --uninstall-extension theme-jacobs-dark-0.1.0.vsix

cursor --uninstall-extension theme-jacobs-dark-0.1.0.vsix && vsce package && cursor --install-extension theme-jacobs-dark-0.1.0.vsix

```

## Credit
Forked from https://github.com/azemoh/vscode-onedark

TODO
add icon
screenshots
license