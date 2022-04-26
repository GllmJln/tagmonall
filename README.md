# Tagmonall patch for dwm

Quick patch for moving all clients (windows) to another monitor. I have no real knowledge of C, this is therefore probably not the most efficient solution, but it works. I just wanted to share this quick and dirty solution because I have seen other people asking for this patch. Feel free to add to suckless website.

# Note

There is a patch called [tagallmon](https://github.com/bakkeby/patches/blob/master/dwm/dwm-tagallmon-6.3.diff) developped by [bakkeby](https://github.com/bakkeby) that accomplishes the same goal.


# Installation

Patch as usual.

```bash

cd dwm/

patch -p1 < dwm-tagmonall-6.2.diff

```
# Credits

Uses the attachbottom function, from the [attachbottom patch](https://dwm.suckless.org/patches/attachbottom/), written by Marshall Mason and Szabolcs Szucs.
