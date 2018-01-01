
# 3rd party scripts and binaries

Collection of useful stuff i use, but do not maintain. 

## Install

  This repository is part of https://github.com/wellspring/bin and is
  automatically recursively cloned from it. Possible to use separately, but 
  the other scripts I maintain are nice-to-have too.

## Content

Shell utils:
- **`mem`**: python script enabling to know how much RAM is currently really 
  being used per program (instead of per process, like `ps` / `top` do) by 
  summing all processes of the same name, and taking care of the shared 
  memory correctly using the most accurate method possible. The sizes are 
  displayed in human format, and a total is added at the end.
- **`repl`**: ruby wrapper to make non-interactive programs be usable like a 
  shell (e.g. `redis-cli`, ...).
- **`sort-by-regex`** / **`esort`**: sort lines using a perl regular expression
  (instead of a column number, like coreutils's `sort` does).

Desktop utils:
- **`alert-desktop-osd`** / **`osd`** / **`xnotify`**: Python script using libX11 to 
  display an on-screen-display message at the specified position.
- **`menu-shutdown`**: small script using `rofi` (or `zenity`) to display a 
  basic Shutdown/Reboot/Hibernate/Suspend/Halt/Lock/Logout/Cancel menu for 
  light tiling wm (like `i3wm`, `bspwm`, `dwm`, `xmonad`, ...) that can be 
  easily controlled using the keyboard!

Terminal utils:
- **`terminal-colors`**: Display a very short grid-summary of 256 terminal 
  colors (8 system colors + 6x6x6 cube + greyscale ramp). It is nice to use 
  to visually test the terminal support, but can also display numbers by 
  passing the _`-n`_ argument (or rgb values with numbers by passing _`-l`_).
- **`ansi-colors-truecolor`** / **`ansi-colors-24bits`**: Display a tiny visual 
  preview of the capabilities of 24bits/truecolor provided by _some_
  terminals.

Net utils:
- **`phantomjs`**: headless webkit, scriptable in javascript.
- **`pubchem.datatool`**: official tool to handle https://pubchem.ncbi.nlm.nih.gov/ data.
- **`Archive.org`** / **`ia`**: Internet archive (www.archive.org) command-line tool.
- **`ncdm`**: NCurses Download Manager (compiled from https://github.com/richardpl/ncdm)


