# Interton-VC4000-EPROM-Multicarts

Experimental EPROM-based carts in 2 flavours for the Interton VC4000 retro console and compatibles, based on 27256.
First one comes with triple DIP-switches and is for 8x4KB games, second comes with quadruple DIP-switches and is for 16x2KB games.
These carts are ESPECIALLY DESIGNED for the Interton VC4000 (and Grundig Super Play 4000 Computer, maybe also others) with the unusual 1x31 connector facing the rear side and are NOT suitable for consoles like Radofin, which are software-compatible, but with different, two-sided connectors. And YES, the front side has NOT an edge connector, this is how it's supposed to be...

Simple schematics, easy to build projects and at a very low cost. An EPROM programmer is needed in order to feed the EPROM with the games required. Just chain eight 4KB (4096 bytes long) or sixteen 2KB (2048 bytes long) game files to each other with some suitable utility proggy (e.g. WinHEX editor for Windoze) and burn the resulting 32KB .bin file to a 27256. I have included two sample 32KB .bin files here, each one suitable for the corresponding cart flavour, ready to be written on empty EPROMs.

Games larger than 4KB are NOT supported and in case you want to include game files with size LESS than 4KB each on the 8x4KB cart version, remember to convert them to exactly 4K by adding some zeros after the end of the game file. The same applies for files with length less than 2048 bytes for the 16x2KB version of the cart. N.B. that the latter (of course) does not support games bigger than 2KB... I was very lazy to try and design an all-in one (with switchable 2 or 4K banks) cart, so I simply made two of them. :-)

NOTE: This PCB has NOT been tested yet by me on real hardware, but the schematic is correct and the connector size is accurate, so why not give it a try?

Disclaimer: No responsibility at all from my side if these don't work for you as expected, or if you blow up your equipment or if you burn your residence/whole neighbourhood trying to use one of these! This is a pure hobbyist project done during my spare time, I am not an expert or professional, so use these 100% at your own risk!
