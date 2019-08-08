# Tmux Cheat Sheet

## Shortcuts

### Sessions

`Prefix + )` - Switch the attached client to the previous session

`Prefix + (` - Switch the attached client to the next session

`Prefix + L` - Switch the attached client back to the last session

`Prefix + s` - **Select new session interactively**

`Prefix + $` - **Rename session**


### Windows

`Prefix + c` - **Create new window**

`Prefix + ,` - **Rename window**

`Prefix + '` - Prompt for the window index

`Prefix + w` - List all windows

### Panes

`Prefix + z` - Zoom/Unzoom pane

`Prefix Alt-Up` -	resize-pane -U 5

`Prefix Alt-Down` -	resize-pane -D 5

`Prefix Alt-Left`	resize-pane -L 5

`Prefix Alt-Right` -	resize-pane -R 5

`Prefix Ctrl-Up`	- resize-pane -U

`Prefix Ctrl-Down` -	resize-pane -D

`Prefix Ctrl-Left` -	resize-pane -L

`Prefix C-Right` -	resize-pane -R

## Plugins

### Tmux Plugins Manager

https://github.com/tmux-plugins/tpm

### Installation

1. Run
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

2. Put at the bottom of `.tmux.conf`
```
run -b '~/.tmux/plugins/tpm/tpm'
```

3. Install plugins by running `Prefix I`

## Sources

1. https://www.freecodecamp.org/news/tmux-in-practice-integration-with-system-clipboard-bcd72c62ff7b/
2. https://leanpub.com/the-tao-of-tmux/read#thinking-tmux

## Inspirations
1. https://github.com/powerline/powerline/
2. https://vanheusden.com/multitail/
3. https://github.com/tmux-python/tmuxp
