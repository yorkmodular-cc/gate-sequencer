## 8-step gate sequencer

**This module is now discontinued - there will be no more made unless there is sufficient demand to justify a new run of boards and panels.**

**Information provided here is provided under the terms of the Creative Commons License Attribution-ShareAlike 4.0 International**

*Construction involves surface-mount components - if you're confident soldering SOIC and 0805-sized components then you'll be OK with this.*

*IMPORTANT* - for best results, use a CD4017 or equivalent as they're capable of handling a 12V supply voltage - 74HC chips and their equivalent have maximum supply voltages of around 5-6V and are not guaranteed to work, not to mention seriously constraining the gate output voltage.

A companion to the 8-step CV sequencer, this module will output gate signals rather than variable CVs.

This more useful than it sounds - individual gate outputs allow you to trigger one (or more, if you're using a mult) module per beat - plus, if you route one of the gate outputs to the reset input of another sequencer you can get odd time signatures - for example, connect gate output 6 to the reset line of an 8-step sequencer and you've got a 5-step pattern.

Gate voltage will depend on how you build the module - using an 8V regulator (7808 or equivalent) and red LEDs will yield a gate voltage of around 6-6.5V so triggering external modules should be relatively stress-free - however, in some cases you may find it necessary to buffer the gate signal first (older Korg SQ-1s and Volcas seem to require their clock signal to be buffered, for example).

Gerber files are provided (in the `gerbers` direc