## 8-step gate sequencer

*Construction involves surface-mount components - if you're confident soldering SOIC and 0805-sized components then you'll be OK with this.*


A companion to the 8-step CV sequencer, this module will output gate signals rather than variable CVs.

This more useful than it sounds - individual gate outputs allow you to trigger one (or more, if you're using a mult) module per beat - plus, if you route one of the gate outputs to the reset input of another sequencer you can get odd time signatures - for example, connect gate output 6 to the reset line of an 8-step sequencer and you've got a 5-step pattern.

Gate output voltage is around 6V, so triggering external modules should be relatively stress-free - however, in some cases you may find it necessary to buffer the gate signal first (older Korg SQ-1s and Volcas seem to require their clock signal to be buffered, for example)