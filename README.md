# Clock-with-flip-flops
Full flip-flop clock with JK-FF
this clock uses 6 7-segments to show hours, minutes, and seconds and uses just JK-Flip-Flops to count and measure time. used flip-flops are 75s112 and to transfer BCD data to 7-segment, 6 BCD to seven-segment parts by the part number of 7447 are used. These FF parts need a clock pulse of 1Hz, to provide this pulse, an ATtiny 13 and a DS1307 are implemented + the CVAVR code.
Also, Flip-Flops(74s112) can be replaced by any other kind of JK or D FF, but the change in designation must be considered.
