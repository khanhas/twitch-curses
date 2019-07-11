# twitch-curses
This is a simple twitch.tv browser / streamlink frontend made with python and ncurses that I hacked together one day. Maybe someone will find it useful.  
The controls should be pretty straightforward.

Fork from: https://gitlab.com/corbie/twitch-curses

Added:
- Sorts channels by language. Open `twitch-cursed.py` and change `lang` variable.
- Sorts catagories by frequency.
- Added language tag before channel name, moved status and added icons for readibility.

![demo](https://i.imgur.com/ySdPA9H.png)

## Installation
Get deps:
```bash
pacman -S python python-pycurl python-urllib3 streamlink
```
Clone and symlink:
```bash
git clone https://github.com/khanhas/twitch-curses
cd ./twitch-curses
chmod +x ./twitch-curses.py
sudo ln -srf ./twitch-curses.py /usr/bin/twitch-curses
```

## License
[WTFPL](https://gitlab.com/corbie/twitch-curses/blob/master/LICENSE)