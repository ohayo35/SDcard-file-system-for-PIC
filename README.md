# SDcard-file-system-for-PIC
This C based SDcard file system for 8 bits PICs is based on the FatFs file system open source project : http://elm-chan.org/fsw/ff/00index_e.html

It has been tested in the following environment :
Software : 
MPLAB X v5.45 IDE,
XC8 v2.31 C compiler,
MCC plugin for MPLAB X v4.0.2  with
Core v5.0.2
MCC FatFs library v1.1.0

Hardware :    
HPC Curiosity board with PIC18F46K42 (ref DM164136 from Microchip),
microSD Click (ref 924 from Mikroelektronika)

The project attached demonstrate how to create a text file and write a couple of sentences in it.
The microSD card can then be easily read on a PC as it uses a standard file system (FAT32)
It uses MCC (MPLAB Code configurator) and makes it simple to port to any other 8 bits PIC device
