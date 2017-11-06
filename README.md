# RC2014-YM2149
My patched PTX Player that will read a PT3 file and play it, press a key to exit.....

I have included assembled binary. Requires that YM2149 at D0 hex.


To assemble, you need to find SJASM, (runs under Windows, command line).


There are a number of undocumented Z80 instructions used in the original PTXPlayer, also uses specific to SJASM
data types, which make it hard to port to other assemblers.


SJASM can be found at:

http://www.xl2s.tk/
