# Linux Xmodmap setup

See the Xkb version for the latest for Linux.

This is an older setup with Xmodmap, not very compatible with modern
desktop environments as this requires the base Dvorak to be loaded
first and then the Xmodmap.

I used this with Xmonad.

```
$ cat local/bin/load-guadvorak
#!/bin/bash
setxkbmap dvorak
xmodmap ~/.guadvorak
```
