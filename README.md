# Mini-Zork

## The Game

_Mini-Zork_ is an interactive fiction game published by [Infocom](https://en.wikipedia.org/wiki/Infocom).

In the later years of the 8-bit era, computer magazines like _Your Sinclair_ and _Commodore Format_ were sold with so-called cover tapes, usually containing a number of games. The November 1990 issue of _Zzap!_, number 67, came with "Magnificent megatape 11", featuring Rimrunner, Thunderforce, SWIV, and, interestingly, Zork. The latter title, advertised as being provided by Activision, was not the full game of _Zork I_, but an abridged version made for distribution on cassette tape. It's also known as _Mini-Zork_ since that's how it's self-described in some text in the game.

_Mini-Zork_ is an abridged version of the earlier _Zork I_. Being released on the sequential cassette medium, it's a single-load program. What this means is that the game had to fit in the 64 kilobytes of memory available to the Commodore 64. To achieve this, prose and puzzles were reduced compared to the original.

This repository is called "Mini-Zork 1" because there was a "Mini-Zork II" found in Infocom's archives but it was apparently never released.

This repository contains the source code for the game. This source code is provided in ZIL (Zork Implementation Language), which was a specialized subset of [MDL](https://en.wikipedia.org/wiki/MDL_(programming_language)), which was itself a dialect of LISP. The ZIL language was created by MIT students and staff. When compiled, the game can run on any implementation of the [Z-Machine](https://en.wikipedia.org/wiki/Z-machine). Infocom used a compiler called ZILCH to compile the source code. That compiler, however, is lost. While there was a [project to bring ZILCH back](https://github.com/ZoBoRf/ZILCH-How-to), currently the only known way to compile this kind of source code is via a project like [ZILF](https://foss.heptapod.net/zilf/zilf/-/wikis/home).

## Version History

| Release | Serial | Type | Obsessive Sources  | Historical Sources   |
| -------:|:------:|:----:|:------------------:|:--------------------:|
|       2 | 840207 |  DEV |  [minizork-r2.zip] |      [minizork-1982] |
|      34 | 871124 |  PUB | [minizork-r34.zip] |      [minizork-1987] |

[minizork-r2.zip]: https://eblong.com/infocom/sources/minizork-r2.zip
[minizork-1982]: https://github.com/historicalsource/minizork-1982/archive/master.zip

[minizork-r34.zip]: https://eblong.com/infocom/sources/minizork-r34.zip
[minizork-1987]: https://github.com/historicalsource/minizork-1987/archive/master.zip
