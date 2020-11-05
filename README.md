# Mac Initial Setup

### Install Command Line Tools for Xcode 

Download it directly from Apple Developer Center here -> [Download](https://developer.apple.com/download/more/?=command%20line%20tools)

After installation you can check if there is a new update available and install it with the commands below

```sh
softwareupdate --list
softwareupdate --all --install --force
```

### Install Homebrew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"  
```

The below line will help you to turn off any analytics comming from Google.

```sh
brew analytics off
```

Finally you can check the health of your current installation with 

```sh
brew doctor
```
