# GreatFET Hardware
This repository contains hardware designs for GreatFET One (codename:
Azalea) and a series of neighbors.  These are:

 * Azalea - the base GreatFET platform
 * Begonia - a neighbor for writing firmware to the IM-Me
 * Crocus - a Nordic nRF24L01+ neighbor
 * Daffodil - a prototyping neighbor
 * Edelweiss - a TI CC1350 neighbor
 * Foxglove - A level shifting neighbor


Most of these designs have a required KiCad dependency:

https://github.com/greatscottgadgets/gsg-kicad-lib

If you are using git, the preferred way to install gsg-kicad-lib is to
use the submodule:

$ git submodule init && git submodule update
