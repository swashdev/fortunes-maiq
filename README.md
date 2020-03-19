fortunes-maiq
=============

This repository hosts files for the `fortune` program for Linux and the BSDs
containing quotes taken from the popular character [M'Aiq the Liar] from
[the Elder Scrolls games].

[M'Aiq the Liar]: https://uesp.net/wiki/General:M%27aiq_the_Liar
[the Elder Scrolls games]: https://elderscrolls.com/

Each file contains all of M'Aiq's various quotations from Morrowind, Oblivion,
Skyrim, and The Elder Scrolls Online, except that most of his greetings have
not been included.

What mysteries will M'Aiq reveal to you?  Only time will tell.

Installation
------------

Copy `maiq` and `maiq.dat` to `/usr/share/games/fortunes/`.  fortune should
include the M'Aiq quotes with its random batch of fortunes now.

To verify that the files were installed correctly, type `fortune -c maiq` and
take note of the file name that it prints out to make sure it's reading the
file from `/usr/share/games/fortune/`.

Optionally, I would suggest editing `~/.bashrc` to run the `fortune` command
when you open a terminal.

Attribution
-----------

All quotes in this file were taken from [the Elder Scrolls games].

The quotes were mined from [the Unofficial Elder Scrolls Pages]' wiki
articles on [M'Aiq the Liar].

[the Unofficial Elder Scrolls Pages]: https://uesp.net/

M'Aiq the Liar belongs solely to [ZeniMax Media Inc].  Please don't Notch me.

[ZeniMax Media Inc]: https://www.zenimax.com/
