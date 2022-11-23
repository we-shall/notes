# Install oh-my-zsh

<br>

What is ZSH?

> Zsh is built on top bash to make it more interactive and customisable.

<br>

### Prereq Install ZSH

```
# for linux
sudo apt-get install zsh
```

OR

```
# for mac
brew install zsh
```

For other OS check:
https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH

### Check for zsh on the machine

```
zsh --version
```

### Run on terminal

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install plugins

1\. Install zsh-autosuggestions

```
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```

2\. Add the following to your .zshrc:

```
source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh
```

REFERERNCES:

- https://ohmyz.sh/
- https://github.com/ohmyzsh/ohmyzsh/
- https://github.com/ohmyzsh/ohmyzsh/wiki
- https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
