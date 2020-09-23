# zsh-bird-completions
ZSH Completion for the BIRD routing daemon


#### Installation
One liner:
`curl https://raw.githubusercontent.com/natesales/zsh-bird-completions/master/_birdc | sudo tee /usr/share/zsh/functions/Completion/Linux/_birdc`

Safer:
```bash
curl https://raw.githubusercontent.com/natesales/zsh-bird-completions/master/_birdc -o /tmp/_birdc
cat /tmp/_birdc # Make sure everything looks ok
sudo mv /tmp/_birdc /usr/share/zsh/functions/Completion/Linux/_birdc
````
