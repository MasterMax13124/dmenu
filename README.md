# dmenu - dynamic menu

This repo contains my personal modified version of [dmenu](https://tools.suckless.org/dmenu). It is intended to be used together with my build of [dwm](https://github.com/MasterMax13124/dwm) and my [dotfiles](https://github.com/MasterMax13124/dotfiles), but can also be used standalone in your setup.

## Features of this build

- dmenu floats in the center of the screen with this [patch](https://tools.suckless.org/dmenu/patches/center/)
- There's a border around dmenu to set it apart from other windows, using [this](https://tools.suckless.org/dmenu/patches/border/)
- Numbers on the right side of the input field indicate remaining options, check [here](https://tools.suckless.org/dmenu/patches/numbers/)
- Finally there's gruvbox colors, because of course there are gruvbox colors, see [patch](https://tools.suckless.org/dmenu/patches/gruvbox/)
	
## Other changes

I haven't made any other real changes myself, aside from enabling the patches by default in the config. Whenever you launch dmenu by itself, it should show up in the center of the screen, in line view mode, with the border around it. That's pretty much it.
