# videoton-vdt-52100-c
This is not my own project, this is gathered data about the terminal Videoton VDT 52100-C terminal. Here I'll upload a pictures of the terminal and its parts, ROM dumps and other data I'll gather while I'm restoring it. At the moment terminal seems to be mainly functional, all ROM has been read, but it seems that it's not supporting the standard escape codes, si I want to explore its firmware to find out how to configure it and how to control it.
This "project" can take a lot of time to be completed.
Main steps of my plan are:
1. to disassemble and to comment the code to understand how it works
2. to format the code so it can be assembled back to its binary code
3. to generate the font image
4. to maybe replace the cyrillic letters with lowercase latin ones because there is no lowercase
5. to design an additional ROM cartridge

The software used for disassembly and for simulating the firmware is Oshnosoft 8085 simulator.
