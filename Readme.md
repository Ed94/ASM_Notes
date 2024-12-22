# Assembly & Related Notes

These notes are focused on assembly language and related tooling (linkers, loaders, etc).

Speficially, those used on the following machines:

* Modern personal computers (MS Windows, Linux, or Mac)
* Video Game Consoles (fourth gen and up)

## David Salomon

https://www.davidsalomon.name

[Assemblers and Loaders (1993)](https://www.davidsalomon.name/assem.advertis/AssemAd.html)  
<img src="./assets/ASSEMBLERS%20AND%20LOADERS%20(upscale%20&%20cleanedup).png" alt="Book Cover" width="320">


## John R. Levine

https://www.johnlevine.com/index.phtml

[Linkers and Loaders (2000)](https://linker.iecc.com)

## Ian Lance Taylor

[20 part Linker Essay (on LWN)](https://lwn.net/Articles/276782/)

## Tools

Order by interest. My preference was on simple tools written in a C-like, data-oriented, or procedural way. I don't want to deal with low level tooling marred by dense language abstractions.

[Zydis](https://github.com/zyantific/zydis)

* [ZASM (Zydis frontend, not to be confused with Z80 assembler...)](https://github.com/zyantific/zasm)

[YASM (Rewrite of (some) of Netwide in C)](https://yasm.tortall.net)

[AsmJit](https://github.com/asmjit)

[FASM](https://flatassembler.net)

[VASM](http://sun.hasenbraten.de/vasm/)

[HLA](https://plantation-productions.com/Webster/HighLevelAsm/index.html)

Everything below is just noted to exist but I don't care for.

[Netwide Assembler](https://www.nasm.us)

[MASM](https://github.com/qb40/masm)

[GAS](https://wiki.osdev.org/GAS)

## Exectuable Formats

* [PE Format](https://learn.microsoft.com/en-us/windows/win32/debug/pe-format?redirectedfrom=MSDN)
* [ELF](https://wiki.osdev.org/ELF)
* [Mach-O](https://github.com/aidansteele/osx-abi-macho-file-format-reference/blob/master/Mach-O_File_Format.pdf)
