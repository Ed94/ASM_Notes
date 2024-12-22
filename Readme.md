# Assembly & Related Notes

These notes are focused on assembly language and related tooling (linkers, loaders, etc).

Speficially, those used on the following machines:

* Modern personal computers (MS Windows, Linux, or Mac)
* Video Game Consoles (fourth gen and up)

# Significant Authorship

These are in alphabetical order by author.

## Brian Robert Callahan

[Demystifying programs that create programs](https://briancallahan.net/blog/20210407.html)

* [Part 1: A disassembler](https://briancallahan.net/blog/20210407.html)
* [Part 2: Starting an assembler](https://briancallahan.net/blog/20210408.html)
* [Part 3: Globals, passes, and error handling](https://briancallahan.net/blog/20210409.html)
* [Part 4: Parsing](https://briancallahan.net/blog/20210410.html)
* [Part 5: Processing our first opcode](https://briancallahan.net/blog/20210411.html)
* [Part 6: Processing more opcodes](https://briancallahan.net/blog/20210412.html)
* [Part 7: Further opcode processing](https://briancallahan.net/blog/20210413.html)
* [Part 8: Finishing opcode processing](https://briancallahan.net/blog/20210414.html)
* [Source](https://github.com/ibara/d80)

## Brian R. Hall

[Assembly Programming and Computer Architecture for Software Engineers](https://brianrhall.com/book/)
<img src="./assets/Assembly Programming and Computer Architecture for Software Engineers (Cover_Ed2).png" alt="Book Cover" width="320">


## Casey Muratori

[Performance-Aware Programming Series](https://www.computerenhance.com/p/table-of-contents)  
<img src="./assets/Computer Enhance banner.jpg" alt="Banner" width="320">

* Part 1: Reading ASM
  * [Instruction Decoding on the 8086](https://www.computerenhance.com/p/instruction-decoding-on-the-8086)
  * [Decoding Multiple Instructions and Suffixes](https://www.computerenhance.com/p/decoding-multiple-instructions-and)
  * [Opcode Patterns in 8086 Arithmetic](https://www.computerenhance.com/p/opcode-patterns-in-8086-arithmetic)
  * [8086 Decoder Code Review](https://www.computerenhance.com/p/8086-decoder-code-review)
  * [Using the Reference Decoder as a Shared Library](https://www.computerenhance.com/p/using-the-reference-decoder-as-a)
  * [Simulating Non-memory MOVs](https://www.computerenhance.com/p/simulating-non-memory-movs)
  * [Simulating ADD, SUB, and CMP](https://www.computerenhance.com/p/simulating-add-jmp-and-cmp)
  * [Simulating Conditional Jumps]()
  * [Simulating Memory]()
  * [Simulating Real Programs]()
  * [Other Common Instructions]()
  * [The Stack]()
  * [From 8086 to x64]()
  * [8086 Simulation Code Review]()

## David Salomon

https://www.davidsalomon.name

[Assemblers and Loaders (1993)](https://www.davidsalomon.name/assem.advertis/AssemAd.html)  
<img src="./assets/ASSEMBLERS%20AND%20LOADERS%20(upscale%20&%20cleanedup).png" alt="Book Cover" width="320">

## Edson Borin

[An Introduction to Assembly Programming with RISC-V](https://riscv-programming.org/book/riscv-book.html)  
<img src="./assets/An Introduction to Assembly Programming with RISC-V.jpg" alt="Book Cover" width="320">

## Ian Lance Taylor

[20 part Linker Essay (on LWN)](https://lwn.net/Articles/276782/)  
<img src="./assets/IAN LANCE 20 part (preview).png" alt="Preview" width="320">

## John R. Levine

https://www.johnlevine.com/index.phtml

[Linkers and Loaders (2000)](https://linker.iecc.com)  
<img src="./assets/LINKERS & LOADERS (cover).png" alt="Book Cover" width="320">

## Jo Van Hoey

[Beginning x64 Assembly Programming: From Novice to AVX Professional](https://link.springer.com/book/10.1007/978-1-4842-5076-1)
<img src="./assets/Beginning x64 Assembly Programming cover.webp" alt="Book Cover" width="320">

## Michael Abrash

[Zen of Assembly Language](https://www.jagregory.com/abrash-zen-of-asm/)  
<img src="./assets/ZEN OF ASSEMBLY LANGUAGE (cover).jpg" alt="Book Cover" width="320">

## nicebyte

[Let's Learn x86-64 Assembly!](https://gpfault.net/posts/asm-tut-0.txt.html)

* [Part 0 - Setup and First Steps](https://gpfault.net/posts/asm-tut-0.txt.html)
* [Part 1 - Metaprogramming in Flat Assembler](https://gpfault.net/posts/asm-tut-1.txt.html)
* [Part 2 - We're Writing a Virtual Machine](https://gpfault.net/posts/asm-tut-2.txt.html)
* [Part 3 - Arithmetic and Logic](https://gpfault.net/posts/asm-tut-3.txt.html)

## Tools

Order by interest. My preference was on simple tools written in a C-like, data-oriented, or procedural way. I don't want to deal with low level tooling marred by dense language abstractions.

[Zydis](https://github.com/zyantific/zydis)

* [ZASM (Zydis frontend, not to be confused with Z80 assembler...)](https://github.com/zyantific/zasm)

[YASM (Rewrite (on some) of Netwide in C)](https://yasm.tortall.net)

* [Design](https://www.tortall.net/projects/yasm/reference/design/design.pdf)
* [User Manual](https://www.tortall.net/projects/yasm/manual/manual.pdf)
* [libyasm](https://www.tortall.net/projects/yasm/reference/libyasm-doc/html/files.html)

[DynASM](https://github.com/Esvandiary/DynASM)

[AssemblyLine](https://github.com/0xADE1A1DE/AssemblyLine)

[AsmJit](https://github.com/asmjit)

* [AsmTK](https://github.com/asmjit/asmtk)

[VASM](http://sun.hasenbraten.de/vasm/)

[FASM](https://flatassembler.net)

[TASM](https://github.com/qb40/tasm)

[HLA](https://plantation-productions.com/Webster/HighLevelAsm/index.html)

Assemblers below are just noted to exist but I don't care for.

[xbyak](https://github.com/herumi/xbyak)

[Keystone assembler framework](https://github.com/keystone-engine/keystone)

[MASM](https://github.com/qb40/masm)

[Netwide Assembler](https://www.nasm.us)

[GAS](https://wiki.osdev.org/GAS)

## Exectuable Formats

* [PE Format](https://learn.microsoft.com/en-us/windows/win32/debug/pe-format?redirectedfrom=MSDN)
* [ELF](https://wiki.osdev.org/ELF)
* [Mach-O](https://github.com/aidansteele/osx-abi-macho-file-format-reference/blob/master/Mach-O_File_Format.pdf)

## Misc

[SBCL: the ultimate assembly code breadboard](https://pvk.ca/Blog/2014/03/15/sbcl-the-ultimate-assembly-code-breadboard/)

[mschwartz's assembly tutorial](https://github.com/mschwartz/assembly-tutorial)

[CppCon 2018: Matt Godbolt “The Bits Between the Bits: How We Get to main()”](https://youtu.be/dOfucXtyEsU)
