# MIDI/O
midi/o is a project that allows user to define in a simple language 
midi routing and so..

It allow user to define a custom mapping from MIDI input to outputs with additional modules
along the way. These nodes can be either generative or not...

- The MIDI/O also has a graphic interface.
- The MIDI/O can be also used iwth e.g. loopMIDI to control the parameters inside of DAW.
Therefore it will have a simple map button which will silence all the traffic and will only
send a midi cc set messages on given channel/cc...

- there will be global inputs such as... 
Key, BPM...
- every module is in its own way a MIDI dvice and there are different types of connections...
e.g.
1. CC Connection
2. Note Connection
3. SysEx Connection ...

MIDI/O will have a custom programmable Nodes.. which compiles to C library and connects to 
the application.

MIDI/O has these generative patches..
1. Arpeggiator
2. Chordify(creates chords from incomming MIDI traffic and will generate a chords out of them).


POSTPONED... learn fookin MAX for ABLETON 