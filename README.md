# tinytetris
80x23 terminal tetris!

![tinytetris gif](animation.gif)

### tinytetris.cpp
This is the 80x23 version. You control it with `a` (left), `d` (right), `w` (rotate),
`s` (drop), and `q` (quit). It depends on `curses.h` (so you'll need to compile with
`-lcurses`, and install curses if you don't already have it) and requires C++11.

### tinytetris-commented.cpp
This one is almost identical to `tinytetris.cpp`, but not minified, and with some
comments to make it easier to read (but it's still tricky to read in certain parts).

### How to install curses?
Debian users install the packages libncurses5-dev libncursesw5-dev.
Pacman and msys2 users install the package ncurses.
Yum and Dnf users install the package ncurses-devel.

### How to compile?
Linux: Install gcc, g++, make, and curses. then run the 'make' command in the directory you copied this repo to.
Windows with msys2: Install gcc, make, and curses. then run the 'make' command in the directory you copied this repo to.
