# Tmux Config

Personal config with custom theme and battery icon in tmux status-right.

## Installation

### Dependencies

**tmux** must be installed

### Manual Installation

Clone the repo:

    $ git clone https://github.com/giorgosioak/tmux-conf.git ~/clone/path
    $ cd ~/clone/path

Backup your current config:

    $ mv ~/.tmux.conf ~/.tmux.conf.backup

Copy files to ~ :

    $ mv .tmux.conf .tmux ~

Reload TMUX environment:

    $ tmux source-file ~/.tmux.conf

You can safely remove ~/clone/path
    
    $ rm -r ~/clone/path 

## What's included

* Less awkward prefix keys : Remap prefix from 'C-b' to 'C-a'.
* Pane Split Commands : Using | and - for splitting panes.
* Easy Config Reloads : 'C-a' + r to reload tmux.
* Fast Pane-Switching : Alt + <arrows> for switching panes.
* Don't allow tmux rename windows automatically
* Custom Theme
* Battery percentage on status-right

![alt text](https://i.imgur.com/0itksnd.png)

## Credits & License

### External Plugins

The [tmux-battery](https://github.com/tmux-plugins/tmux-battery) plugin is part of the [tmux-plugins](https://github.com/tmux-plugins) organisation.

### Theme and key binds

By Ham Vocke's [A Guide to Customizing your tmux.conf](http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/).

Theme was created by reddit user [/u/dothebarbwa](https://www.reddit.com/user/dothebarbwa).

### Maintainer

 - [George Ioakeimidis](https://github.com/giorgosioak)

### License

[MIT](LICENSE.md)
