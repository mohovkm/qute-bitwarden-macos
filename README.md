# qute-bitwarden-macos

#### This script is an add-on for [qutebrowser](https://github.com/qutebrowser/qutebrowser). It was rewritten for MacOS users. Instead of `dmenu`, `rofi` and other addons, it uses apple script to show choices and password prompt.

Original script: https://github.com/qutebrowser/qutebrowser/blob/master/misc/userscripts/qute-bitwarden

### Requriements:

- keyring
- click
- tldextract

### Usage:

1. Place this script inside `~/.qutebrowser/userscripts/qute-bitwarden` and go to this folder
2. Make this file executable `chmod +x qute-bitwarden`
3. Create virtualenv `python3 -m venv .venv`
4. Install requirements `python3 -m install -r requirements.txt`
5. Change the first line inside executable `qute-bitwarden` to match your `.venv` directory
6. Open qutebrowser and execute following command to use script:
```
:spawn --userscript qute-bitwarden
```
