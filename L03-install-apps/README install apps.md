# Softare installation

- copy the install-apps.sh script to your local hard drive and open a terminal at its folder

- edit install-apps.sh

```zsh
nano install-apps.sh
```

For information about the casks and formulae in the script you can search for them here

https://formulae.brew.sh/

Remove any casks (UI applications) or formulae (command line tools) not required for your course, or which you already have installed.

Then

- save using control-O (letter O)
- exit using control-X

- make the script executable

```zsh
chmod u+x ./install-apps.sh

```

- execute the script to install the packages

```zsh
./install-apps.sh
```
