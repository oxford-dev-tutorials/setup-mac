# Links

VS Code Extensions Marketplace Docs

https://code.visualstudio.com/docs/configure/extensions/extension-marketplace

# How to install extensions using a script

- copy

  - install-extensions.sh
  - vscode-extensions-list.txt

to your local hard drive and open a terminal at its folder

- edit vscode-extensions-list.txt

```zsh
nano vscode-extensions-list.txt
```

For information about the extensions you can search for them here

https://marketplace.visualstudio.com/VSCode

Remove any extensions you don't want

Then

- save using control-O (letter O)
- exit using control-X

- make the extensions installation script executable

```zsh
chmod u+x ./install-extensions.sh

```

- execute the script to install the packages

```zsh
./install-extensions.sh
```
