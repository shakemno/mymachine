#MyMachine
A shell script to setup a Mac OS X development machine, customized only for my personal needs, based on the awesome work by **@thoughtbot** [https://github.com/thoughtbot/laptop](https://github.com/thoughtbot/laptop).


##Install - Mac OS X

Please install Xcode via App Store and the Xcode command line tools ```xcode-select --install```

Read, then run the script, sudo needed:

	bash <(curl -s https://raw.githubusercontent.com/shakemno/mymachine/master/mymachine)
	
	
##What it sets up

- Alcatraz the package manager for Xcode
- Bundler for managing Ruby libraries
- CocoaPods the dependency Manager for Objective C.
- Homebrew for managing operating system libraries
- ImageMagick for cropping and resizing images
- Rbenv for managing versions of Ruby
- Ruby Build for installing Rubies
- Ruby stable
- Zsh as your shell + oh-my-zsh
 
---

- reminder.txt for Appstore apps
- default background-image/user-icon from _assets
- dotfiles from _assets
- brew casks:
  -	alfred
  - appcleaner
  - cfxr
  - dropbox
  - firefox
  - google-chrome
  - gitx
  - sublime-text
  
  
##TODO
- fetch dotfiles...
- oh-my-zsh check
- pre-commit hook to build
- extend user setup https://github.com/ptb/Mac-OS-X-Lion-Setup/blob/master/setup.sh
- extend user setup https://github.com/rudolph9/dotfiles/blob/master/.osx


##License

Copyright (c) 2014 shakemno.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

