This repository is a fork of Original "(https://github.com/caarlos0/dotfiles.fish)"


This fork includes modifications to suit private and specific requirements.

Acknowledgments:

Gratitude to Original Author/Owner's [caarlos0](https://github.com/caarlos0/dotfiles.fish) for his excellent work on the original project.Thanks

## Installation

### Dependencies

First, make sure you have all the following installed:

- `git`: to clone the repository
- `curl`: to download files
- `tar`: to extract downloaded files
- `fish`: the shell
- `sudo`: some configurations may need that
- `vscode`: some configurations may need that
### Install

Then, run these steps:

```console
git clone https://github.com/caarlos0/dotfiles.fish.git ~/.dotfiles
cd ~/.dotfiles
./script/bootstrap.fish
```

> All changed files were backed up with a `.backup` suffix.

#### Update

To update, you need to `git pull` and run the bootstrap script again:

```console
cd ~/.dotfiles
git pull origin master
./script/bootstrap.fish
```

## Recommended Software

- [`alacritty`](https://github.com/alacritty/alacritty) a cross-platform, OpenGL
  terminal emulator;
- [`bat`](https://github.com/sharkdp/bat) a cat(1) clone with wings;
- [`delta`](https://github.com/dandavison/delta) for better git diffs;
- [`fd`](https://github.com/sharkdp/fd) a simple, fast and user-friendly
  alternative to `find`;
- [`fzf`](https://github.com/junegunn/fzf) for a fuzzy-finder;
- [`gum`](https://github.com/charmbracelet/gum) A tool for glamorous shell
  scripts;
- [`gh`](https://github.com/cli/cli) for more GitHub integration with the
  terminal;
- [`grc`](https://github.com/garabik/grc) to colorize command's outputs;
- [`neovim`](https://neovim.io) extensible Vim-based text editor;
- [`starship.rs`](https://starship.rs) the shell prompt we are using;

  To install them all:
```console
sh -c "$(curl -fsSL https://starship.rs/install.sh)"
sudo apt install fish grc fzf zoxide fd-find exa bat alacritty  neovim

