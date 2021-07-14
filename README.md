# Wall wart ±12V power supply and bus board

This is a power supply based on the [MFOS wall wart supply](http://musicfromouterspace.com/analogsynth_new/WALLWARTSUPPLY/WALLWARTSUPPLY.php). Differences are:

* Added polyfuses
* Added LEDs
* Input is either barrel jack or pluggable terminal block, with another pluggable terminal block for daisy chaining
* Output is a (non pluggable) terminal block
* Regulators are vertical, with space for Tayda A-5093 heat sinks
* Board is shorter and wider (100 x 61 mm) to keep fabbing price low

Note that unlike usual Eurorack supplies, this one provides no +5 V rail. (Of course there are almost no Eurorack modules that use the +5 V rail these days, and no Kosmo modules do.)

I've built a version of this board and it works. I found a few minor issues in the process, the worst of which was an incorrect footprint for the fuses with too small holes for the leads — no other problems affecting functionality. I've since updated the layout to fix the issues I've found. I haven't built that version yet, but it should be fine.

# Sonosus' Bus Board Version
I've designed a snap off bus board into the PCB. The board size is just large enough to be eligible for a free coupon at [a certain PCB fab house](https://allpcb.com) (no, I am not affiliated with them in any way, this board will probably work with JLCPCB, OSHPark, PCBWay, Eurocircuits, etc, etc, etc. 
You can use it as a power supply with integrated bus board, or snap them apart and wire seperately.
