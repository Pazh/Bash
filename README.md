# 1Bash v2.0

Linux Bash Customization

## Install

```bash
# clone project
export ONE_BASH=~/1bash
git clone https://github.com/Pazh/Bash.git $ONE_BASH

# copy user config
cp -av $ONE_BASH/inputrc ~/.inputrc
cp -av $ONE_BASH/bash_profile ~/.bash_profile
cp -aiv $ONE_BASH/gitconfig ~/.gitconfig

# Edit yout name/email in git config
nano ~/.gitconfig
```

## Customize Logo

Put your logo or any welcome message in `~/.1bash_logo`.

```bash
nano ~/.1bash_logo
```

[Generate your own logo](http://patorjk.com/software/taag)

## Upgrade

Just pull the 1bash git repository.

```bash
cd $ONE_BASH
g pl
```
