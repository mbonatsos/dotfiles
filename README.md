# my .files

## Installation 
Download file into home directory
```bash
curl -o ~/.gitconfig.aliases https://raw.githubusercontent.com/mbonatsos/dotfiles/master/git/.gitconfig.aliases
```
Include this file in .gitconfig
```bash
git config --global include.path "~/.gitconfig.aliases"
```
