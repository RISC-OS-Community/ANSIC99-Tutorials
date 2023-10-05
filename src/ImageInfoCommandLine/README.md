# Image Information Command Line tool in ANSI C99 on RISC OS

This simple code example shows how to use process names passed via the command line on RISC OS, dealing the file types, opening files for reading, calling
operating system SWIs (SysCalls).

The source code is split into 3 smaller pieces and so requires linking together after being compiled into a single object file. This is done with the help of a Makefile.

## How to build the code

Ensure you have the Acorn/ROOL DDE suite installed on your RISC OS system and that RISC OS Desktop Filer has seen it.

Git clone this repository in a way that can be reached by your RISC OS system, if you do not know how to do this have a look at [this set of videos](https://www.youtube.com/playlist?list=PLEnraaJ9VQfWDl5T4D0P51pG89KRzj0n1) on the matter that can help you to find the best approach for you to use git with your RISC OS.

Then, from your RISC OS system, double click on the !Mk task obey file which is provided. This will use amu (the Acorn Make Utility) to read the Makefile and compile each of the source files in the subdirectory named `c`.

For a full description of how the code works have a look at this video [here](https://www.youtube.com/watch?v=K91Pfd3dvRI)

Enjoy!
