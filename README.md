# My Dev Environment (MacOS)

- [My Dev Environment (MacOS)](#my-dev-environment-macos)
  - [Applications](#applications)
  - [Terminal](#terminal)
  - [Browser and Extensions](#browser-and-extensions)
  - [Productivity Tips](#productivity-tips)

---

## Applications
* Evernote - for note-taking
* [BoostNote](https://boostnote.io/): This is my goto app for keeping useful snippets of code/terminal. It supports Markdown and syntax highlighting so it's got a big advantage over OneNote.
* Visual Studio Code + some uncommon extensions below you may find useful:
  * [One Dark Pro theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
  * [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer): Nice UI improvement to help with reading your own spagethi code :D
  * [Code Time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode): Keeps track of how much time you spent coding vs. looking at memes.
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
* Postman
* Magnet
* FUSE (Support for other file systems): https://osxfuse.github.io
* Zoom
* [Alfred 4](https://www.alfredapp.com/) with Powerpack is a must for productivity hacks on MacOS.
  * tldr: https://github.com/cs1707/tldr-alfred
  * Terminal Finder: https://github.com/LeEnno/alfred-terminalfinder
  * GitHub: https://github.com/gharlan/alfred-github-workflow
  * IP Address: https://github.com/alexchantastic/alfred-ip-address-workflow
  * Colors: http://www.packal.org/workflow/colors
  * Encode/Decode: https://github.com/willfarrell/alfred-encode-decode-workflow
  * Host File Manager: http://www.packal.org/workflow/hosts-file-manager
  * Process Killer: https://github.com/nathangreenstein/alfred-process-killer
* Trello
* NordVPN
* Tomighty
* Clocker
* [Clipy](https://github.com/Clipy/Clipy): This is an awesome tool for managing clipboard history and common snippets/URLs you copy/paste.

## Terminal
* [iTerm2](https://www.iterm2.com/features.html): This is a must for any power user of terminal.
* [OhMyZsh](https://github.com/robbyrussell/oh-my-zsh) with [Powerline fonts](https://github.com/powerline/fonts): Nice aesthetics for the terminal and useful plugins.
  * ZSH_THEME="cobalt2" (https://github.com/wesbos/Cobalt2-iterm)
  ![My Terminal](https://i.imgur.com/NuU9yds.png)
  * plugins=(zsh-syntax-highlighting zsh-autosuggestions)
  * aliases:
 ```
 alias zshconfig="code ~/.zshrc"
 alias ohmyzsh="code ~/.oh-my-zsh"
 alias cat="bat"
 alias ls="k -h"
 alias k="k -h"
 ```
* [htop](https://github.com/hishamhm/htop): replacement for `top`. Much prettier and more practical with useful key bindings:

  * **P**: Sort by CPU Usage

  * **M**: Sort by Memory Usage

  * **F4**: Filter by string

* [bat](https://github.com/sharkdp/bat): Pretty much a replacement for `cat` (which prints contents of files) but with syntax highlighting, line numbers and more.
* [ncdu](https://dev.yorhel.nl/ncdu): Get information about disk space.
* [fd](https://github.com/sharkdp/fd/): Simple replacement for `find`.


## Browser and Extensions
* LastPass: Simply the best and most reliable password manager.
* Checker Plus for Gmail
* Checker Plus for Calender
* JWT Debugger
* uBlock Origin
* Zoom scheduler
* Dictionary Anywhere
* User Agent Parser
* WhatRuns
* Stylish
* Requestly
* Wikiwand
* Tampermonkey

## Productivity Tips
* Desk setup + Room
  * Make sure your setup is as ergonomic as possible (See this [video](https://www.youtube.com/watch?v=MTL8EBBH69o)). Nothing destroys productivity more than a neck/back pain.
  * Take more frequent breaks by geting up from your chair. I follow the [Pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) and it's helped me greatly stay more alert and less tired during work. You can use one of the many Apps or Browser extensions to remind you to take your break or get back to work. I personally use [Tomighty](http://www.tomighty.org) with the below settings:
  ![Tomight Settings](https://i.imgur.com/SYmmDz7.png)

