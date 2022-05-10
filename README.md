Были внесены изменения из [рекомендаций](https://askubuntu.com/a/1352435) и протестирована работоспособность на Debian с Nautilus 42.1.1 

*Nautilus Backspace*
-----------------------
Brings back the Backspace shortcut to Nautilus

Installation
-----------------------
1) Install [Nautilus Python](https://wiki.gnome.org/Projects/NautilusPython) (`apt-get install python3-nautilus` in Debian-based distributions)
 
2) Download `Backspace-Back.py` and put it here: `.local/share/nautilus-python/extensions/`

(you might have to create this directory first)

3) Restart Nautilus (`killall nautilus`)
