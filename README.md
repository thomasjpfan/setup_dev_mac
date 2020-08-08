# My OSX dev setup

1. `xcode-select --install`
1. Install homebrew.
1. `brew install ansible`
1. `ansible-galaxy install -r requirements.yml`
1. `ansible-playbook osx_setup.yml -i inventory -K`
1. `chsh -s /usr/local/bin/zsh`
1. `curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`
1. `nvim +PlugInstall +qall`
1. Install [vscode](https://code.visualstudio.com) and sync extensions.
1. Install [karabiner-elements](karabiner-element).
1. Install [anaconda](https://www.anaconda.com/download/#macos).
1. Setup ssh keys
1. Setup backups
