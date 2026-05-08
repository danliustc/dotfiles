## Dotfiles

Use [chezmoi](https://www.chezmoi.io/) to manage the dotfiles.

## Contents

* zsh: oh-my-zsh based shell config, local proxy helpers, Homebrew setup, and uv-first Python defaults.
* vim: minimal Vim config without plugins.
* Hammerspoon: macOS automation, currently input method auto-switching.
* tmux: geohot-style prefix and TPM plugins.
* git: aliases, conditional work configs, Git LFS filter config, and `git lg`.
* pip: pip mirror config.
* neovim: older Lua config kept for reference.

Emacs is managed in a separate repository.

## Python

Python is managed with [uv](https://docs.astral.sh/uv/). The old pyenv shell hooks are disabled in `dot_zprofile`, and `UV_MANAGED_PYTHON=1` is exported by default.

Reference:
* [Bastian's Dotfiles](https://github.com/venthur/dotfiles)
* [dotfiles](https://github.com/chaneyzorn/dotfiles)
* [chezmoi](https://www.chezmoi.io/)
