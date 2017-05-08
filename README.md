# bitar
Guitar hero to Midi performance controller for Open Source 'vanilla' Pure Data which can be found http:\\puredata.info

This instrument was created to leverage the most I could out of a guitar hero controller for live performance.
It takes advantage of the Guitar hero accellerometers to give you two continuous controllers (excellent for playing with modulation, 
filters and fx levels or whatever else you might think of.)

To get the most playability you should be able to proficiently count in binary.  This allows for easy playing of scales.
To get a full 4 octaves of playability, the lowest note is played with no fret buttons.
For convenience, you get to select the octave, Key and Mode that is output from the controll

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
