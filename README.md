# MC33390 J1850VPW Module
This module uses the MC33390 Class B Serial Transceiver from Freescale. This IC is obsolete, but you can easily find it on old GM clusters to salvage or from overseas grey-market vendors. This will work with most 5v logic microcontrollers. For the microcontroller, it performs the same as my standalone J1850VPW transceiver. https://github.com/garnerm91/J1850VPW-Transceiver. If you want to develop something new around the design, I would recommend using that as your reference; it uses no obsolete parts. 

## Schematic
It's the PDF labeled MC33390.PDF

## Gerbers
REVA.zip has them in it. By the way it has PCBWAY in the silkscreen because they sponsored the project.

## Code
This project works with it: https://github.com/garnerm91/Arduino_J1850VPW

## Where to find the IC?
GM used these a lot. GM marked the MC33390 as "56585":
* 03-07 GM Instrument Clusters
* 2004 and newer Trailblazer Clusters
* Some GM Radios
