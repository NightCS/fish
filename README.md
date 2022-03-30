# Fish

This is a theme for fish using the night colorscheme (using terminal colors, depend with the colors you have in your terminal configuration)

![demonstration](./misc/demonstration)

## Installation

Backup your configurations and copy files:

```sh
if test -d $HOME/.config/fish; then mv $HOME/.config/fish $HOME/.config/fish.BAK; fi
git clone https://github.com/NightCS/fish fish
mv fish $HOME/.config
```

Done!

## Activating ghost prompt

If you have a font that have the icon of the ghost, you can replace the linux icon with the ghost icon with this commands:

```sh
cd $HOME/.config/fish
rm functions/fish_mode_prompt.fish
mv functions/fish_mode_prompt_ghost.fish functions/fish_mode_prompt.fish
```

Done!
