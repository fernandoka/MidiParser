# MidiParser
This program take part in the development of my final university project. I have made this program to be able to understand MIDI files format. Consequently I was able to create a hardware desing of a digital piano which can play the corresponding songs stored in a MIDI file.

Link to the MIDI hardware player project (digital piano implemented in a FPGA), which use real time wavetable synthesis: https://github.com/fernandoka/Digital-Piano-VHDL-MIDI-Player

The MIDI examples files It have been downloaded from [Musescore](https://musescore.com/)

Example of use: 
> ./midi_parser.elf -F midiFiles/Papermoon.mid > output.txt
