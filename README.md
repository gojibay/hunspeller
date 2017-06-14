# hunspeller

## INSTALLATION

### Installing hunspell via pip on OSX Mavericks

PYTON OSX MAC PIP HUNSPELL MAVERICKS
In case you are having trouble installing hunspell (not finding hunspell.h or -lhunspell) via pip on you mac, these steps worked for me:

```
$ brew install hunspell
$ export C_INCLUDE_PATH=/usr/local/include/hunspell
$ sudo ln -sf /usr/local/lib/libhunspell-1.4.a /usr/local/lib/libhunspell.a
$ pip install hunspell
```
cf https://coderwall.com/p/nhmyeg/installing-hunspell-via-pip-on-osx-mavericks

## Ressources

https://cgit.freedesktop.org/libreoffice/dictionaries/tree/
