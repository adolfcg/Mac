# Mac Initial Setup

### Install Command Line Tools for Xcode 

Normally you can install the Command Line Tools for Xcode with the command: 

```sh
xcode-select --install
```

However some users are experiencing an error comming with the legend >> **"Can't install the software because it is not currently available from the Software Update server"**


A current work arround at the moment is to download the DMG package directly from Apple Developer Center here -> [Download](https://developer.apple.com/download/more/?=command%20line%20tools)

After installation you can check if there is a new update available and install it with the commands below.

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

Finally you can check the health of your current installation with:

```sh
brew doctor
```
