# RFID TAGs (PCB's and supporting documents)

## RFID_NFC_TAG_9x6
A simple small 9x6 mm PCB which uses two additional components to make up an RFID tag.
These are intended for use on model railways but applicable to other things.

## Description
Schematic KiCad files are included along with the GERBER files ready to send to a fab house for building.
It is recommended to have these panelized by the fab house into an array.
e.g.: 10 x 10 array for 100 tags per PCB). With the typical minimum order of 5 PCBs this will get you 500 tags.
Note that if the fab house can get the parts these PCB's could be ordered 'built' (With an associated cost of course)

For home assembly some experience with surface mount component assembly is recommended (hot plate method). 

## Technical
Designed for 13.56 MHz using the ISO15693 (vicinity Card) standard.
    Uses an NXP SL2S2602FTBX three pin IC (very small)
    And a 43pF capacitor for antanna matching ( 0402 SMD = very small )

## Other Equipment
For a complete RFID solution a tag also needs a suitable reader in order to energize the tag and get the information from it. 
For testing purposes I am using the StaRFIshRail hardware designed by the late Martin Snashell (no longer available)
