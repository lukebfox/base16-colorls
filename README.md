# base16-colorls

This repository is meant to work with
[chriskempson/base16](https://github.com/chriskempson/base16).
It provides a simple template that can be used with the base16 color schemes to
generate a functional config file for
[athityakumar/colorls](https://github.com/athityakumar/colorls),
a prettifier for 'ls' written in ruby.

To use, you can copy one of the config files in colors/ or use curl:

```
mkdir -p ~/.config/colorls
curl https://raw.githubusercontent.com/lukebfox/base16-colorls/master/colors/base16-default-dark.yaml >> ~/.config/colorls/dark_colors.yaml
```
