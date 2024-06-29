# My Config AKA Dotfiles

Nth attempt to store my Linux configs

## Keyboard Layout

My preferred keyboard layout is the basic US with some tweaks to write all
symbols used in Catalan.

I prefer the US layout because the brackets, commas, etc., are in more
convenient positions for programming.

I don't want to use the regular Spanish layout because I need to type a space
after a grave (`) or apostrophe ('). I type those characters more often than
accents.

These are the tweaks I made to the US layout:

* `AltGr` + `` ` `` and then `a`, `e` or `o` to produce `à`, `è` or `ò`
* `AltGr` + `'` and then `e`, `i`, `o` or `u` to produce `é`, `í`, `ó` or `ú`
* `AltGr` + `~` (`SHIFT` + `` ` ``) and then `n` or `N` to produce `ñ` or `Ñ`
* `AltGr` + `l` to produce `ŀ`
* `AltGr` + `L` to produce `Ŀ`
* `AltGr` + `c` to produce `ç`
* `AltGr` + `C` to produce `Ç`

### Install on GNU/Linux

I tested it in Debian 11 and Ubuntu 24.04, both using Gnome.

Copy the directory `xkb` to `~/.config`

Go to `Settings` &rarr; `Keyboard`. In `Input Sources` click the plus sign and
select `English`. In the list that appears you should see a variant called
`Catalan (US)`.
