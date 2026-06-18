# ADHDE zsh theme

Zsh theme for [Attendtion Deficit Hyperactivity Desktop Environment](https://github.com/Senderman/adhde)

![Preview](./preview.png)

# Installation

## Plain zsh

Clone this repository to any location on your PC, then add to your `.zshrc`:

```bash
fpath+=(/path/to/this/directory)
autoload -Uz promptinit
promptinit
prompt adhde
```

If you want to change the accent color, which is cyan by default:

```bash
prompt adhde red
```

## With [Antidote](https://getantidote.github.io/)

Same as for plain zsh, but instead of modifying fpath directly, add the following line to your plugins file:

```
Senderman/adhde-zsh-theme kind:fpath
```

# Misc
Inspired by [OMZ's fox theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fox.zsh-theme)

