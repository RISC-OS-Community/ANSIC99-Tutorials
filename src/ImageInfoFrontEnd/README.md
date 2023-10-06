# Image Information FrontEnd tool in ANSI C99 on RISC OS

This project builds on the earlier Image Information Command Line tool by adding a desktop front end written using the FrontEnd module. This module allows you to quickly add a graphical user interface by describing the interactions in a text file (called 'Desc'), and is usually provided in the !System resource with RISC OS.

The Makefile is also extended to copy in the commonly found application resources such as Sprites, Help text, and window designs.

## How to build the code

Ensure you have the Acorn/ROOL DDE suite installed on your RISC OS system and that RISC OS Desktop Filer has seen it.

Git clone this repository in a way that can be reached by your RISC OS system, if you do not know how to do this have a look at [this set of videos](https://www.youtube.com/playlist?list=PLEnraaJ9VQfWDl5T4D0P51pG89KRzj0n1) on the matter that can help you to find the best approach for you to use git with your RISC OS.

Then, from your RISC OS system, double click on the !Mk task obey file which is provided. This will use amu (the Acorn Make Utility) to read the Makefile and compile each of the source files in the subdirectory named `c`. The Makefile will then create a standard layout RISC OS application, !ImageInfo.

For a full description of how the code works have a look at this video [here](https://www.youtube.com/watch?v=TBD)

Enjoy!
