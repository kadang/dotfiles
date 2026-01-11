# dotfiles

This repo contains configuration files for various bits of software I use:

- hyprland
- Neovim
- tmux
- VS Code
- zsh

It will also contain a shell script that creates symlinks to these files locally from where the programs expect them to be.

## hyprland


## Neovim

- Location of neovim configuration: `${HOME}/.config/neovim/init.lua`:


## tmux

- File: `${HOME}/.tmux.conf`


## VS Code/VS Codium

- Files: `settings.json`, `keybindings.json`
- Location of user settings files: `${HOME}/.config/Code/User/` or `${HOME}/.config/VSCodium/User/`


### Extensions

It's possible to install extensions on the command line:

```shell
code --install-extension <extension-id-1> <extension-id-2>...
# or
vscodium --install-extension <extension-id-1> <extension-id-2>...

```

I use the following extensions regularly:

- AsciiDoc: `asciidoctor.asciidoctor-vscode`
- Astro: `astro-build.astro-vscode`
- Git Graph: `mhutchie.git-graph`
- Java: `oracle.oracle-java`
- Vale: `chrischinchilla.vale-vscode`
- Live Server: `ritwickdey.liveserver`

I've also installed these extension, but I don't use them as much:

- Gemini CLI companion: `google.gemini-cli-vscode-ide-companion`
- Code Spell Checker: `streetsidesoftware.code-spell-checker`
- Container Tools: `ms-azuretools.vscode-containers`
- GitLens: `eamodio.gitlens`
- QML: `bbenoist.qml`


### Theme

My theme of choice at the moment is Gruvbox Medium Dark:

- `jdinhlife.gruvbox`


## Z shell

