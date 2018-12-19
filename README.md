# base16-i3

This repository is meant to work with
[chriskempson/base16](https://github.com/chriskempson/base16).
It provides a simple template that can be used with the base16 color schemes to
generate a functional config file for
[sway/sway](https://github.com/swaywm/sway),
a tiling and dynamic window manager for wayland.

To use, you can copy the config files or use curl. You can then include the files:

```
include base16-default-dark-color-scheme

bar {
…
include base16-default-dark-bar-colors
}
```

It is important that you import the color scheme before you import the bar colors.

