# Developer Setup

## Terminal

Preferences

- Profiles
	- Text
		- Cursor
			- Color: bright green [0,255,0]
			- Vertical Bar
			- [x] Blink cursor
	- Keyboard
		- [x] 'Use Option As Meta Key' (so you can use Alt+Arrow Keys to jump over/select/delete entire words)

## Oh-My-Zsh

Since macOS Catalina, Mac's ship with `zsh` as the default shell. In order to make the Terminal experience nicer you should use [oh-my-zsh](https://ohmyz.sh).

`sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`


## Xcode command-line tools

In order to run more interesting commands (e.g. `git`) in the Terminal you need to install the Xcode command-line tools, you can do so even without fully installing Xcode:

`xcode-select --install`

## SSH key

Generate an RSA public-key pair

`ssh-keygen -t rsa`


## Homebrew

install Homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

### Cask

install programs:

- VisualStudio Code :`brew cask install visual-studio-code`

### Jekyll for GitHub pages blogging

install via Ruby:

```zsh
brew install rbenv

gem install --user-install bundler jekyll
```
- serve blog on localhost:4000: ``

## Other Terminal commands


## Sourcetree

Preferences:

- Git
	- [x] Stage files on double click
- Custom Actions
	- Menu Caption: *pull-rebase-autostash*
	- shortcut: **⌘P**
	- Script to run: `git`
	- Parameters: `pull --rebase --autostash`
