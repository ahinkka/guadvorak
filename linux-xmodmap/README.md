# Latest Linux setup

This is an older setup with Xmodmap, not very compatible with modern
desktop environments. I used this with Xmonad.

```
$ cat local/bin/load-guadvorak
#!/bin/bash
setxkbmap dvorak
xmodmap ~/.guadvorak
```
