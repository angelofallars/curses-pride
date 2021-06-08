# ✨🏳️‍🌈 curses-pride 🏳️‍🌈✨

![code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)

 
A simple terminal application, for showing off your fabulousness with pride flags.

## Installation
```bash
sudo cp ./src/pride.py /usr/local/bin
sudo mv /usr/local/bin/pride.py /usr/local/bin/pride
sudo cmhod +x /usr/local/bin/pride
```

## Usage
```bash
usage: pride [-h]
             [-c | -r | -f {agender,aromantic,asexual,bisexual,gay,lesbian,non-binary,pansexual,transgender}]

curses-pride shows your favourite pride flags in a terminal of your choice.

optional arguments:
  -h, --help            show this help message and exit
  -c, --cycle           cycles through all of the various pride flags
  -r, --random          shows a random pride flag
  -f {agender,aromantic,asexual,bisexual,gay,lesbian,non-binary,pansexual,transgender}, --flag {agender,aromantic asexual,bisexual,gay,lesbian,non-binary,pansexual,transgender} shows a pride flag of your choice
```