# AnalogFluxReader
A daughter board to the cheap Cypress  FX2LP demo boards for reading floppy fluxes in analog domain.

This is still very much work in progress. The idea with this project is to read to those problematic Memorex 651 disks that I so far has been unsuccessful in reading.

Instead of using the read detector in the drive the idea is to connect the differential signal from the head to the board and the do the all processing in the host PC. 

![Schematic](https://raw.githubusercontent.com/MattisLind/AnalogFluxReader/master/AnalogFluxReader.png)

The board sits on top of one of those small Cypress FX2LP baords that can be purchased from China cheaply. The FX2LP chip provide a programmable USB interface with high performance. Giving the possibility to sample the A/D converter with up to 48 MSMPS.

![FX2LP](https://raw.githubusercontent.com/MattisLind/AnalogFluxReader/master/fx2lp.jpeg)


