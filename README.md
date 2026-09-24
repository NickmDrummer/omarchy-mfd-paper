# Omarchy MFD Paper

A dark green and orange theme for Omarchy, inspired by the visual style of MFD Paper.

The theme uses a deep green background, muted gray-green foreground colors, and orange accents for highlights and important UI elements.

![Preview](https://github.com/NickmDrummer/omarchy-mfd-paper/blob/master/preview.png "Preview")

## Installation

Install the theme directly with Omarchy:

```bash
omarchy theme install https://github.com/NickmDrummer/omarchy-mfd-paper.git
```

The theme will be installed and applied automatically.

To apply it again later:

```bash
omarchy theme set omarchy-mfd-paper
```

## Related configurations

This repository contains only the Omarchy theme.

If you also want to use my Neovim or Ghostty configuration, see the following repositories:

- [Neovim](https://github.com/NickmDrummer/nvim)
  
- [Dotfiles](https://github.com/NickmDrummer/dotfiles)
  

Those repositories contain personal configuration and may require additional
adjustments depending on your system. The readme files in both repositories are not updated. Use them at your own risk.

If you just want the Ghostty and Neovim themes without using my dotfiles follow the next sections:

### Ghostty MFD-Paper palette:

Omarchy generates the Ghostty configuration from the theme palette when
possible. The following configuration is provided for reference or for users
who want to apply the palette manually. Please note that this is my own adaptation of MFD-Paper and may not be perfect.

- First create the conf file in ~/.conf/ghostty/themes/mfd-paper
  
- Then, in the ghostty conf file just change the theme:
  

```
theme = mfd-paper
```
- Reload Ghostty to see the changes

  
mfd-paper:
```
background = #001407
foreground = #ADB7B2
cursor-color = #c2c9c5
selection-background = #1a2c20
selection-foreground = #001407

palette = 0=#001407
palette = 1=#f66d22
palette = 2=#528d42
palette = 3=#779d50
palette = 4=#628e56
palette = 5=#ff9246
palette = 6=#4a924c
palette = 7=#ADB7B2
palette = 8=#646a65
palette = 9=#ff8f2b
palette = 10=#6fb54d
palette = 11=#97c65c
palette = 12=#81b66a
palette = 13=#ffad45
palette = 14=#66bb5b
palette = 15=#c2c9c5
```

### Neovim theme

The theme used in neovim is the MFD-Paper variant from Kungfusheep.

You can see his repository here to install it: [mfd.nvim](https://github.com/kungfusheep/mfd.nvim)
