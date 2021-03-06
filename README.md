# somafm-cli <sub><sup>| Listen to SomaFM in your terminal via pure bash</sup></sub>
[![version](http://img.shields.io/badge/version-v0.1.0-blue.svg)](https://github.com/rockymadden/somafm-cli/releases)
[![versioning](http://img.shields.io/badge/versioning-semver-blue.svg)](http://semver.org/)
[![branching](http://img.shields.io/badge/branching-github%20flow-blue.svg)](https://guides.github.com/introduction/flow/)
[![license](http://img.shields.io/badge/license-mit-blue.svg)](https://opensource.org/licenses/MIT)
[![pm](http://img.shields.io/badge/pm-zenhub-blue.svg)](https://www.zenhub.io/)
[![chat](http://img.shields.io/badge/chat-slack-blue.svg)](https://rockymadden-slack.herokuapp.com/)
[![circleci](https://circleci.com/gh/rockymadden/somafm-cli.svg?style=shield)](https://circleci.com/gh/rockymadden/somafm-cli)

[![asciicast](https://asciinema.org/a/40541.png)](https://asciinema.org/a/40541)

Be sure to help keep SomaFM commercial-free and on the air with your
[support](https://somafm.com/support/)! Groove Salad, Drone Zone, Cliqhop, Secret Agent, Space
Station Soma, Digitalis, PopTron, Suburbs of Goa and Illinois Street Lounge are trademarks of
SomaFM.com, LLC.

## Installation

### Via Homebrew:

```bash
$ brew tap rockymadden/rockymadden
$ brew install somafm-cli
```

### Via compiling from source:

```bash
$ git clone git@github.com:rockymadden/somafm-cli.git
$ cd somafm-cli
$ make
$ make install
```

## Usage

```bash
$ somafm --help
Usage:
  somafm channels
  somafm listen <channel> [--quality=<low|high|highest>]

Core Commands:
  channels    List channels
  listen      Listen to channel
```

## Examples and Recipes

### List channels:

```bash
$ somafm channels
groovesalad | 1535 listeners | A nicely chilled plate of ambient/downtempo beats and grooves.
dronezone | 682 listeners | Served best chilled, safe with most medications. Atmospheric textures with minimal beats.
spacestation | 332 listeners | Tune in, turn on, space out. Spaced-out ambient and mid-tempo electronica.
indiepop | 307 listeners | New and classic favorite indie pop tracks.
lush | 283 listeners | Sensuous and mellow vocals, mostly female, with an electronic influence.
secretagent | 237 listeners | The soundtrack for your stylish, mysterious, dangerous life. For Spies and PIs too!
deepspaceone | 195 listeners | Deep ambient electronic, experimental and space music. For inner and outer space exploration.
u80s | 154 listeners | Early 80s UK Synthpop and a bit of New Wave.
bootliquor | 96 listeners | Americana Roots music for Cowhands, Cowpokes and Cowtippers
beatblender | 92 listeners | A late night blend of deep-house and downtempo chill.
poptron | 86 listeners | Electropop and indie dance rock with sparkle and pop.
suburbsofgoa | 84 listeners | Desi-influenced Asian world beats and beyond.
sonicuniverse | 83 listeners | Transcending the world of jazz with eclectic, avant-garde takes on tradition.
seventies | 77 listeners | NEW! Mellow album rock from the Seventies. Yacht friendly.
bagel | 73 listeners | What alternative rock radio should sound like.
defcon | 72 listeners | Music for Hacking. The DEF CON Year-Round Channel.
folkfwd | 70 listeners | Indie Folk, Alt-folk and the occasional folk classics.
thetrip | 63 listeners | Progressive house / trance. Tip top tunes.
illstreet | 59 listeners | Classic bachelor pad, playful exotica and vintage music of tomorrow.
digitalis | 59 listeners | Digitally affected analog rock to calm the agitated heart.
fluid | 58 listeners | NEW! Drown in the electronic sound of instrumental hiphop, future soul and liquid trap.
thistle | 54 listeners | Exploring music from Celtic roots and branches
missioncontrol | 53 listeners | Celebrating NASA and Space Explorers everywhere.
dubstep | 48 listeners | Dubstep, Dub and Deep Bass. May damage speakers at high volume.
cliqhop | 43 listeners | Blips'n'beeps backed mostly w/beats. Intelligent Dance Music.
7soul | 39 listeners | Vintage soul tracks from the original 45 RPM vinyl.
sf1033 | 30 listeners | Ambient music mixed with the sounds of San Francisco public safety radio traffic.
earwaves | 23 listeners | Spanning the history of electronic and experimental music from the early pioneers to the latest innovators.
brfm | 22 listeners | From the Playa to the world, back for the 2015 Burning Man festival.
doomed | 22 listeners | Dark industrial/ambient music for tortured souls.
covers | 18 listeners | Just covers. Songs you know by artists you don't. We've got you covered.
metal | 14 listeners | NEW! From black to doom, prog to sludge, thrash to post, stoner to crossover, punk to industrial.
sxfm | 5 listeners | Music from bands who will be performing at SXSW, one of the biggest and best music festivals in the world. [explicit]
```

### Listen to Groove Salad:

```bash
$ somafm listen groovesalad
A: 00:05:19 Cache: 10s+96k
```

### Listen to Groove Salad at highest quality:

```bash
$ somafm listen groovesalad --quality=highest
A: 00:02:25 Cache: 9s+72k
```

## License
```
The MIT License (MIT)

Copyright (c) 2016 Rocky Madden (https://rockymadden.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
