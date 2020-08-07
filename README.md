<h1 align="center">WELLCOME TO THE CONTRACT GENERATOR</h1>
<p align="center"><img src="https://i.imgur.com/J6z094u.gif" width="562" alt="example"></p>

Command-line tool for contract generation at University Housing

## Feature
* Easy to use 
* Developer can be disturbed any time 🎉
* I don't know what else 🤷‍♂️

## Install
Install HomeBrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
<p align="center"><img src="https://i.imgur.com/0cFYHNT.gif" width="562" alt="install brew"></p>

Install nessesary packages
```bash
brew install coreutils
brew install fx
brew install gnu-sed
brew install jq
```
<p align="center"><img src="https://i.imgur.com/BX5InY8.gif" width="562" alt="brew install"></p>

Install oh-my-zsh for better terminal experience
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Add alias for faster navigation
```bash
echo "alias cdc=\"cd ~/Google\ Drive\ File\ Stream/Shared\ drives/Customer\ Care/Templates/contract\"" >> ~/.zshrc
```

## Usage
Navigate to contract folder using above alias
```bash
cdc
```
Run
```bash
./the_one_script.sh -h
USAGE: ./the_one_script.sh [options] email [email2...]
Options are:
    -h      help
    -y      open all generated contract when finished
    -u      company name
    -k      generate kamer type contract
    -a      generate apartment type contract
```
