# `.zshrc` Config

Zsh setup with TRAMP support, custom paths, plugins, and useful aliases.

## Features

- **TRAMP-safe**: Disables prompt on `TERM=dumb`
- **Paths**: Adds `cargo`, `pnpm`, `spicetify`, etc.
- **Oh My Zsh**: Uses `agnoster`, with plugins like `git`, `zsh-autosuggestions`
- **Aliases**: Handy shortcuts (`ls`, `vim`, `tmux`, `clockin`, etc.)
- **Startup**: Runs `startx`, `neofetch`, `tmux`, and `ls` on TTY login

## Structure

- Oh My Zsh: `~/dotfiles/zsh/.oh-my-zsh`
- Custom: `~/dotfiles/zsh/omz-custom`

## Tools

- [`eza`](https://github.com/eza-community/eza)
- [`bat`](https://github.com/sharkdp/bat)
- [`neofetch`](https://github.com/dylanaraps/neofetch)
- [`tmux`](https://github.com/tmux/tmux)
