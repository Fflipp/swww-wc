# swww-wc
Wallpaper changing tool for use with swww

Systemwide wallpapers are stored in /usr/share/swww-wc/wallpapers
User-specific wallpapers are stored in ~/.wallpapers

## Options
-h Prints help
-u Manages user-level wallpapers
-s manages system-level wallpapers

## wc-swp
`wc-swp [-h] [-u] [-s] <PATTERN>`
Changes the active wallpaper to the filename matched by PATTERN.
If multiple matches are found, a selection dialogue is presented.

## wc-add
`wc-add [-h] [-s] <PATTERN>`
Adds a file to ~/.wallpapers, creating the directory if it does not yet exist.
-s instead adds the file to /usr/share/swww-wc/wallpapers, requires root permissions.

## wc-del
`wc-del [-h] [-u] [-s] <PATTERN>`
Removes a file from the managed wallpapers directories with a filename matched by PATTERN.
If multiple matches are found, a selection dialogue is presented.
Attempting to remove a wallpaper located in /usr/share/swww-wc/wallpapers requires root permissions.
