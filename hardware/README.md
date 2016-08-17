# GreatFET Hardware
This directory contains hardware designs for GreatFET One and a series of
neighbours.  These are:

 * GreatFET One - the base GreatFET platform
 * Begonia - a neighbour for writing firmware to the IM-Me
 * Crocus - a Nordic nRF24L01+ neighbour
 * Daffodil - a prototyping neighbor
 * Edelweiss - a TI CC1350 neighbor
 * Foxglove - A level shifting neighbour


Most of these neighbours have a required KiCad dependency:

https://github.com/greatscottgadgets/gsg-kicad-lib

If you are using git, the preferred way to install gsg-kicad-lib is to use the
submodule:

$ git submodule init && git submodule update
