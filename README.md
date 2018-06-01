
# macOS Setup  

inspired by [https://github.com/taniarascia/mac](https://github.com/taniarascia/mac)

This is a simple list of instructions to make setting up your Apple computer as fast and efficient as possible for front end web development.

---

## Preferences

- **Keyboard > Text >** Disable "Correct spelling automatically".
- **Security and Privacy > Firewall >** On
- **Security and Privacy > General >** App Store and identified developers
- **File Sharing >** Off

### Show Library folder

```shell
chflags nohidden ~/Library
```

### Show hidden files

This can also be done by pressing `command` + `shift` + `.`.

```shell
defaults write com.apple.finder AppleShowAllFiles YES
```

### Show path bar

```shell
defaults write com.apple.finder ShowPathbar -bool true
```

### Show status bar

```shell
defaults write com.apple.finder ShowStatusBar -bool true
```

## Base setup
```
sh mymachine
````

## XCode
```
manully install xcode, makes the process a lot easier...
```

## Brewfile
```
brew bundle
```

---

### Review dotfiles/sshtoogle.sh
