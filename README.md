# zsh-bird-completions
ZSH Completion for the BIRD routing daemon

[![asciicast](https://asciinema.org/a/361361.svg)](https://asciinema.org/a/361361)

#### Installation on ohmyzsh
One liner:
```bash
curl https://raw.githubusercontent.com/natesales/zsh-bird-completions/master/_birdc | sudo tee /usr/share/zsh/functions/Completion/Linux/_birdc
```

Safer:
```bash
curl https://raw.githubusercontent.com/natesales/zsh-bird-completions/master/_birdc -o /tmp/_birdc
cat /tmp/_birdc # Make sure everything looks ok
sudo mv /tmp/_birdc /usr/share/zsh/functions/Completion/Linux/_birdc
```

Make sure to load the completion by running `compinit` in your `~/.zshrc` file.
