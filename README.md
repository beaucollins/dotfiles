## Dotfiles

### Setup

```zsh
git init --bare $HOME/.dotfiles
alias dot='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
dot config status.showUntrackedFiles no
echo "alias dot='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'" >> ~/.zshrc
```

### Inspired by

https://www.atlassian.com/git/tutorials/dotfiles
