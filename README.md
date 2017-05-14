# bitar
Guitar hero to Midi performance controller for Open Source 'vanilla' Pure Data which can be found http:\\puredata.info

This instrument was created to leverage a guitar hero controller as a MIDI live performance instrument.
It takes advantage of the Guitar hero accellerometers to give you two continuous controllers (excellent for playing with modulation, filters and fx levels or whatever else you might think of.)

To get the most playability you should be able to proficiently count in binary.  This allows for easy playing of scales.
To make it somewhat easier, it is confined to (selectable) diatonic modes.  Using all 5 buttons (More than 4 full octaves of playability can be acheived. 

For convenience a GUI is provided that enables visual feedback of important parameters.  From there, you select the octave, Key and Mode and MIDI channel, assign tilt and rotation to midi cc's, and can select various 'performance modes' for different playing styles. 

Hardware Requirements:
This project assumes you have 
1) an XBOX360 Wireless Receiver
2) Xbox360 Guitar Hero Controller
3) A raspberry pi or some other linux box.
4) Optional - Some form of Midi interface to hookup to:
 a) Some form of Midi sound generator 
 b) or software synths.

Software Requirements:
1) Miller Pucket's pure data.
2) xbox.drv installed on your system to access the xbox controller data.
3) patchage(optional but makes things easier.)
