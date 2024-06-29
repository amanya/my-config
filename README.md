# My config AKA dotfiles

Nth atempt to store my Linux configs

## Keyboard layout

My preferred keyboard layout is the basic US with some tweaks to write all
symbols used in catalan.

I prefer the US layout because the brackets, commas, etc are in more convenient
position for programming.

I don't want to use the regular spanish layout because I need to type a space
after a grave (`) or apostrophe ('). I type more often those characters than accents.

Those are the tweaks I make to my layout:

* `AltGr` + `` ` `` and then `a`, `e`, `o` to produce `à`, `è`, `ò`
* `AltGr` + `'` and then `a`, `e`, `i`, `o`, `u` to produce `é`, `í`, `ó`, `ú`
* `AltGr` + `l` to produce `ŀ`
* `AltGr` + `L` to produce `Ŀ`
* `AltGr` + `c` to produce ``
* `AltGr` + `C` to produce ``
* `AltGr` + `~` (`SHIFT` + `\``) and then `n` to produce `ñ`

### Install on GNU Linux

I only tested it in Debian 11 and Ubuntu 24.04, both using Gnome.

Copy the directory `xkb` to `~/.config`

Go to `Settings` &rarr; `Keyboard`. Under `Input Sources` add a new one, select
`English` and you should see a variant called `Catalan (US)`.
