# This repository contains the code and schematic for a DIY MIDI to CV converter. I installed this converter into a home-built analog synthesizer, allowing me to play the synthesizer with my Yamaha CP50 keyboard over MIDI.

- The MIDI to CV converter includes the following outputs:

Note CV output (88 keys, 1V/octave) using a 12-bit DAC
Note priority (highest note, lowest note, or last note) selectable with jumper or 3-way switch
Pitch bend CV output (1.0v +/- 1.0V) octabe up or down
Velocity CV output (0 to 5V)
Control Change CV outout (0 to 2V) suitable for a CEM or AS  based VCA
Trigger output (5V, 20 msec pulse for each new key played)
Gate output (5V when any key depressed)
Clock output (1 clock per quarter note, 20 msec 5V pulses)
Read the MIDI channel from 4 toggle switches, can be replaced with a HEX rotary switch or bank of 4 dip switches.

When building and testing the Elkyam MIDI to CV I noticed the volatge was out and it seems he subtracts 21 from the note, I removed this and fixed the bottom note failure.

