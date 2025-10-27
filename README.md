# Termux Style

<p align="left">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/ddCeka/termux-style?style=for-the-badge">
</p>

Simple script to change color-schemes and fonts for [Termux](https://termux.com) terminal emulator.

> **`termux-style` provides color-schemes and powerline-ready fonts to customize the appearance of the Termux terminal.**

### How to install

Follow the steps below - 

```bash
# Go to home dir - 
cd $HOME

# Clone this repository (use `gh repo clone ddCeka/termux-style` if you want to use the GitHub CLI)- 
git clone https://github.com/ddCeka/termux-style

# Change to termux-style dir -
cd termux-style

# To install it, run -
./install

# And follow the steps, it'll be installed on your system.
```

### Run

Run `style` & select the right option -

```bash
$ style

    ┌──────────────────────────────────────────────────┐
    │░▀█▀░█▀▀░█▀▄░█▄█░█░█░█░█░░░░░█▀▀░▀█▀░█░█░█░░░█▀▀░░│
    │░░█░░█▀▀░█▀▄░█░█░█░█░▄▀▄░▄▄▄░▀▀█░░█░░░█░░█░░░█▀▀░░│
    │░░▀░░▀▀▀░▀░▀░▀░▀░▀▀▀░▀░▀░░░░░▀▀▀░░▀░░░▀░░▀▀▀░▀▀▀░░│
    └──────────────────────────────────────────────────┘
    
    [C] Colors (count)
    [F] Fonts (count)
    [R] Random
    [D] Download
    [I] Import
    [Q] Quit
    
    [Select Option]: 
```

### Features

+ 500+ color-schemes.
+ 20 Nerd patched fonts and more.
+ Randomly change color-schemes.
+ Download font from [NerdFont repo](https://github.com/ryanoasis/nerd-fonts).
+ Import color-schemes from *local file* or *file URL*.
+ Set colors and fonts in place.

### Use Download
```bash
    [Select Option]: d
    ...
    33) IBMPlexMono
    34) Inconsolata
    35) InconsolataGo
    ...
    q) type q to quit
    
    [Select Option]: eg: 34

    [*] Reloading Settings...
    [*] Applied Successfully.
```

To install fonts using the menu:
- All fonts are loaded on terminal so you can pick any font you want
- Choose one or more fonts *(by index/number)* to install
- Hit Return/Enter to install the selected fonts
- Type 'q' to quit
- The full list of font are [here](all_font.txt)
<br />

### Use Import
```bash
    [Select Option]: i

    [1] Local File (Enter path to file)
    [2] Internet File (Enter File URL)

    [Select Option]: 2

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/ddCeka/termux-style/master/colors/gruvbox-dark.properties

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://raw.githubusercontent.com/ddCeka/termux-style/master/colors/gruvbox-dark.properties`) of the color-scheme.
<br />

### FYI
- An `uninstall` script is also added, in case you want to remove this program.
- Again... If you can improve it, sure...
- Have fun!
