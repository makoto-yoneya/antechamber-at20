# antechamber-at20 patch

Patch file for [antechamber][1] ver. 1.27

## Functions

This patch replaces the old antechamer-1.27 codes (including dat except mopac) to the correspondings in newer [AmberTools20][2].

Build executables contains antechamber and related tools, tleap, resp (from AmberTools20) and mopac (from antechamber-1.27) instead of sqm in AmberTools20.

## Prerequisites

antechamber-1.27 source: [antechamber-1.27.tar.gz][3]

### Installing

`patch -p1 < antechamber-1.27-at20.patch`

in the top source directory and make.

## Creater

Makoto Yoneya

## License

Same as original antechamber-1.27 (GPLv2) and AmberTools20 (LGPLv3).

[1]: http://ambermd.org/antechamber/antechamber.html
[2]: https://ambermd.org/AmberTools.php
[3]: http://ambermd.org/antechamber/antechamber-1.27.tar.gz
