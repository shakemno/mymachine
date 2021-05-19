
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

### Screenshot location

```shell
defaults write com.apple.screencapture location PATH
killall SystemUIServer
```

## Base setup
```shell
sh mymachine
```

## XCode
```
manully install xcode before the next step, makes the process a lot easier...
```

## Brewfile
```
brew bundle
```

### go2shell settings
```
open -a Go2Shell --args config
```

---

## Notes

- admin user https://support.apple.com/en-us/HT204012

- Review dotfiles/sshtoogle.sh

- www.defold.com

- [brewfile docs](https://homebrew-file.readthedocs.io/en/latest/index.html)

- ****AppCleaner****_3.5
