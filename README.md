# New Macbook Checklist
My setup for a new work Mac device.


## App directory

- [ ] Brave Browser
- [ ] Slack
- [ ] Iterm2
- [ ] Zoom
- [ ] 1Password
- [ ] Magnet



## CLI Setup


## IDE Setup

### Install XCode Tools

`xcode-select --install`

### Install Brew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

### CLI Essentials

__cli tools__

`brew install wget curl git htop pure httpie neovim tree gh podman docker docker-compose go python terraform terragrunt kustomize helm zsh-syntax-highlighting`

__oh my zsh__

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

`git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`

`git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

### Fonts

__Nerd Fonts__

```
brew tap homebrew/cask-fonts
brew install --cask font-hack-nerd-font
```


