# Installation Steps

- Install neccessary stuff

```
# Install Starship
brew install Starship

# Clone Config
git clone https://github.com/KunalHS/kunalkaterminal ~/.config/starship/

```

- Add config to shell rc file (for eg : .zshrc)

```
eval "$(starship init zsh)"
export STARSHIP_CONFIG=~/.config/starship/starship.toml
```
