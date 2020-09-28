# base16-colorls

This repository is meant to work with
[chriskempson/base16](https://github.com/chriskempson/base16).
It provides a simple template that can be used with the base16 color schemes to
generate a functional config file for
[athityakumar/colorls](https://github.com/athityakumar/colorls),
a prettifier for 'ls' written in ruby.

If you've already themed your terminal with a base16 template, then it is not advised to theme colorls with this template. In this scenario, options set to standard colors such as red, green, blue, e.t.c. will automatically render as the correct colors for whatever theme you're running.

Otherwise, to use you can copy one of the config files in colors/ or use curl:

```
mkdir -p ~/.config/colorls
curl https://raw.githubusercontent.com/lukebfox/base16-colorls/master/colors/base16-default-dark.yaml >> ~/.config/colorls/dark_colors.yaml
```
