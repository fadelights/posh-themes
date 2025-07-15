# posh-themes
Custom themes for Oh My Posh.

Most themes were initially part of the default set of themes
provided by [Oh My Posh](https://ohmyposh.dev/) -- now tweaked 
and tuned to suit my needs.

## Usage
After adding the following lines to your (my?) shell `.rc` file;
e.g. `.zshrc`
```bash
export POSH_THEMES="$HOME/.cache/oh-my-posh/themes"
export POSH_CUSTOM_THEMES="$HOME/.cache/oh-my-posh/custom-themes"
eval "$(oh-my-posh init zsh --config $POSH_CUSTOM_THEMES/lambda.omp.json)"
```
and restarting the shell session, clone this repo inside it.
```bash
git clone https://github.com/fadelights/posh-themes.git $POSH_CUSTOM_THEMES
```
