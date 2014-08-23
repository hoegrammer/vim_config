# What this provides
- 4 spaces instead of tabs
- Auto-indentation can be toggled on and off with Ctrl-i
- Line numbers that can be toggled on and off with Ctrl-n
- Javascript syntax checking on save

I find the toggling useful when copying and pasting using the mouse (numbers off to copy, smartindent off to paste).

# Where to put the files

## Global install (for all users; requires root privieges)

Copy `vimrc.local`, the `autoload` directory (as a directory, with its contents) and the `plugin` directory (ditto) into `/etc/vim`.

## Home directory install (for one user)

Copy `vimrc.local` into `home/you` and rename it `.vimrc`. Or just append its contents to an existing `.vimrc`.

Copy the the `autoload` directory (as a directory, with its contents) and the `plugin` directory (ditto) into `/home/you/.vim`.
