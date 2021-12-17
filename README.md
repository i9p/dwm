# 🖥 *dwm*

window manager for "neurodivergent" people

## patches

+ pywal support
+ vanitygaps
+ statuscmd

## keybindings

+ ModKey is bound to `super`
+ `super+shift+enter` for terminal
+ look at `config.h` for all keybindings

## building

+ clone this repository
+ replace `i9p` in `#include "/home/i9p/.cache/wal/colors-wal-dwm.h"` (`config.h` - line 21) with your username
+ change `*launchercmd[]` to your program launcher
+ execute `make clean install` as root

