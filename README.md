# SOIC-24 to DIP-24 Adapter
## Currently untested - this line will be removed once I have a chance to test it
This is basic adapter PCB for using SOIC-24 chips (SMD) as DIP-24 chips (through-hole), made in KiCad.

The adapter is designed to be more or less the same size as a regular DIP-24 IC.

It's especially useful for ICs available in an SOIC-24 package but no longer in a DIP-24 package, such as modern 6116 RAM chips.

There is no decoupling capacitor on the board as it's expected that the main board will already have them.

## Fabrication
Gerber files are provided. Default settings (2 layers, etc.) on fabrication websites such as JLCPCB and PCBWay should suffice.

Map files and pick-and-place files are also included.

## Building
2x 1x12 male header pins are required, plus an SOIC-24 IC of your choice.

It is recommended to solder the SOIC-24 first, as soldering the header pins first will give less clearance for the IC, especially when using a soldering iron.

## Legal
This project's copyright is owned by Gare Ltd., and uses the CERN Open Hardware Licence Version 2 (Strongly Reciprocal).

Complete sources of licensed works and modifications must be made public, notices and license must be preserved, and contributors provide an express grant of patent rights.

No warranty is provided for this project. Responsibility for using this product legally and safely is up to the end user.

&copy; Gare Ltd.
