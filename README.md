# zsh-setup

Install zsh
```
sudo apt install zsh
```

Install antigen
```
mkdir -p $HOME/.antigen
curl -L git.io/antigen > .antigen/antigen.zsh
```

Copy sample .zshrc
```
cp .zshrc.sample ~/.zshrc
```

Switch shell to zsh
```
sudo chsh -s /usr/bin/zsh username
```

Spawn new shell and... voilà
