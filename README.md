# My Config AKA Dotfiles

Nth attempt to store my Linux configs

## Keyboard Layout

I don't want to use the regular Spanish layout because I need to type a space
after a grave (`) or apostrophe ('). I type those characters more often than
accents.

My preferred layout is the basic US with some tweaks to write the special
symbols used in Catalan.

I prefer the US layout because the brackets, commas, etc., are in more
convenient positions for programming.

The position of the dead keys for the acute accent and the diaresis are the
same than in the Mac layout (`e` and `u`) because I find it easier to type than
`'` and '"`.

These are the tweaks I made to the US layout:

* `AltGr` + `` ` `` and then `a`, `A`, etc.,  to produce `à`, `À`, etc.
* `AltGr` + `e` and then `a`, `A`, etc., to produce `á`, `Á`, etc.
* `AltGr` + `u` and then `a`, `A`, etc., to produce `ä`, `Ä`, etc.
* `AltGr` + `l` to produce `ŀ`
* `AltGr` + `L` to produce `Ŀ`
* `AltGr` + `c` to produce `ç`
* `AltGr` + `C` to produce `Ç`
* `AltGr` + `n` to produce `ñ`
* `AltGr` + `N` to produce `Ñ`
* `AltGr` + `.` to produce `·`

### Install on GNU/Linux

I tested it in Debian 11 and Ubuntu 24.04, both using Gnome.

Copy the directory `xkb` to `~/.config`

Go to `Settings` &rarr; `Keyboard`. In `Input Sources` click the plus sign and
select `English`. In the list that appears you should see a variant called
`Catalan (US)`.

### Bonus: Mac layout

I want to use the same keyboard settings when I work on Mac, so I created a
keyboard layout using [Ukelele](https://software.sil.org/ukelele/).

Copy [Catalan.keylayout](misc/mac-keyboard-layout/Catalan.keylayout) and
[Catalan.icms](misc/mac-keyboard-layout/Catalan.icms) to `~/Library/Keyboard
Layouts/`, restart your computer and you should be able to add a Catalan input
source.
