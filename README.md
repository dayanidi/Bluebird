Bluebird
========
Desktop Suite for Xfce
----------------------
URL: http://shimmerproject.org/our-projects/bluebird/

Copyright 2009–2012 Pasi Lallinaho, Simon Steinbeiß

Bluebird is dual-licensed as GPLv2 or later and CC-BY-SA 3.0 or later.

Contributors:
 * Satyajit Sahoo
 * Markus Klinga
 * Lawand

Bluebird was the default theme in Xubuntu 10.10.

The Bluebird desktop suite includes:
- GTK+ themes
- xfwm theme
- metacity theme (by Oleg Olegovich)

### Install without admin privileges

```
./autogen.sh --prefix=$HOME/.local
make install
```

### Install for all users

```
./autogen.sh
sudo make install
