# NES-Power-Board
A PCB that will fit in place of the stock NES frontloader's RF module.
***
This PCB will replace the stock RF modulator box. It will have different connector options for outputting audio and video, as well as a breakout for the channel select switch.

I plan to support:
* composite video with mono audio
* composite video and "stereo" audio (standard 3 RCA TV connection)
* RGB + composite using a Retrofixes SNES style multiout connector.  (Requires existing RGB mod) This will be my version.
* RGB output directly to the Framemeister's 8-pin mini DIN connector. (Requires existing RGB mod)

The first two options require no modification to the chassis. All other versions will require some chassis modification, but it will minimal.

This PCB is designed specifically with Tim Worthington's NESRGB board in mind. The channel select switch will have a breakout so that it can be used as a palette selector switch.
***
# To-Do List for Rev 3
- [x] Flip ribbon connector. It will make the ribbon lay flatter (already did this for rev 2 doh!)
- [x] Check all through holes before sending to board house!
- [x] Change routing of RGB traces and audio traces completely
- [x] Separate video signals from audio signals to help avoid the static issue with the noise channel (may try 4 layer)
- [ ] Fix mounting hole location (may need to move J2)
- [x] C4 and C6 collide with heatsink of U1
- [x] Move components to bottom (working from the top is more difficult after installed)
- [x] Add extra surface mount ribbon connector, 1.27 mm pitch
- [ ] Test composite output (check if transistor bandwidth is sufficient)
- [ ] Band pass filter?
