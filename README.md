# photon_original

This is the "original" Photon source code.

Anything in assembly (pod roms, etc) is Z80 assembler that ran on the [NSC800](https://www.cryptomuseum.com/spy/fs5000/files/NSC800.pdf).

The game computer and data computer are written in a BASIC dialect. Based on what I can tell, it's for the
[IBM Basic Compiler](http://bitsavers.trailing-edge.com/pdf/ibm/pc/languages/6172216_BASIC_Compiler_Mar82.pdf) (you can find a copy of the compiler [here](https://winworldpc.com/product/ibm-personal-computer-basic-compiler/10))

The pod roms were in separate directories (spod14, spod16, and spod16ns) which I applied to the 'pod' directory as successive commits with the source file renamed to 'spod.src' so that you can see the progression.

## Where did this come from?

I can't really remember; some guy who knows a guy? I believe I came into posession sometime in 1993.

## Will it work?

I believe the POD roms would work in the beta system (it's commented somewhere that the spod16 roms are "GR20", which is pre-laser-phaser).
