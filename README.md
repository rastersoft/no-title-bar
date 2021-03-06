# No Title Bar

An extension for GNOME Shell that merges the activity bar and the title bar of maximized windows.

## Install From Source

```
make install
gnome-shell-extension-tool -e no-title-bar@jonaspoehler.de
```

Restart GNOME Shell by pressing <kbd>Alt</kbd>+<kbd>F2</kbd> and entering <kbd>r</kbd>.

## Dependencies

This extension depends on Xorg's `xprop` and `xwininfo` utilities. If not already
present on your system, these can be installed using:

- Debian/Ubuntu: `apt install x11-utils`
- Fedora/RHEL: `dnf install xorg-x11-utils`
- Arch: `pacman -S xorg-xprop`

## Credits

This is based on the no-title-bar extension by franglais125 (https://github.com/franglais125/no-title-bar), which itself 
is a fork of the Pixel-Saver extension, by @deadalnix: https://github.com/deadalnix/pixel-saver
