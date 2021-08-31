# listnonfree
Bash script to list installed proprietary programs on arch linux.  
This script uses parabola's blacklist, selecting only the [nonfree] and [uses-nonfree] lines, not the [branding] or simmilar ones.

https://wiki.parabola.nu/Blacklist

## dependencies
- bash
- printf 
- curl
- grep
- cut
- pacman
