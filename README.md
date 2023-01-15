# Completions for cheat.sh

[cheat.sh](https://github.com/chubin/cheat.sh) is the only cheat sheet you will ever need. This adds oh-my-zsh-compatible completions.

The completions are from [the official completions](https://github.com/chubin/cheat.sh#tab-completion).

## Installation

### Oh My ZSH

Clone the repo.

``` zsh
cd ~/.oh-my-zsh/custom/plugins
git clone git@github.com:thirteen37/chtsh-completions
```

Add `chtsh-completions` to your `.zshrc` plugin list `plugins=(... chtsh-completions)`

### zgen or zgenom

``` zsh
zgen load thirteen37/chtsh-completions
```
