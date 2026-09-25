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
# Custom mfd-paper adaptation for Ghostty 
# This is my custom mfd-paper theme. It preserves almost all of the original colors, with a few subtle adjustments and a striking orange accent. Combined with the BetterCRT shader, the result is absolutely stunning!
palette = 0=#ff4e40
palette = 1=#003008
palette = 2=#002611
palette = 3=#003C08
palette = 4=#002611
palette = 5=#003008
palette = 6=#003C08
palette = 7=#002611
palette = 8=#ff4e40
palette = 9=#003008
palette = 10=#002611
palette = 11=#003C08
palette = 12=#002611
palette = 13=#003008
palette = 14=#003C08
palette = 15=#002611

# Original background color: #BBC5B7
# Blue filter intensity: 
# 10%= #BDC6AB - 15% = #BEC6A5 - 20% = #BFC79F
background = #BBC5B7
foreground = #002611
cursor-color = #ff4e40
selection-background = #ff4e40
selection-foreground = #002611
```

### Neovim theme

The theme used in neovim is the MFD-Paper variant from Kungfusheep.

You can see his repository here to install it: [mfd.nvim](https://github.com/kungfusheep/mfd.nvim)
