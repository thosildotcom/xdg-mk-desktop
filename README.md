# Usage:

```
usage: xdg-mk-desktop [-h] -n NAME -g GENERIC_NAME -e EXECUTABLE -i ICON -m
                         COMMENT -c CATEGORIES
                         filename

This program will help you to create a .desktop file.

positional arguments:
  filename

optional arguments:
  -h, --help            show this help message and exit
  -n NAME, --name NAME
  -g GENERIC_NAME, --generic_name GENERIC_NAME
  -e EXECUTABLE, --executable EXECUTABLE
  -i ICON, --icon ICON
  -m COMMENT, --comment COMMENT
  -c CATEGORIES, --categories CATEGORIES
```

## example:

    xdg-mk-desktop -n "My Name" -g "My generic name" -e /usr/bin/x-terminal-emulator -i /usr/share/icons/gnome/scalable/apps/utilities-terminal-symbolic.svg -m "open terminal" -c system my_term.desktop

You still have to put this file somewhere to be available on your system, ex: ~/.local/share/applications/

# Requirements:
* pip: pyxdg
* CentOS: python2-pyxdg.noarch
* Debian: python-xdg

# Further:

https://www.freedesktop.org/wiki/Specifications/desktop-entry-spec/

---
_made with ❤_
