
MRCS-IOX32
  
I/O expander (IOX) boards have been updated to version 2.3. Based on customer feedback, and our design and installation experience, the changes were made to provide more efficient and flexible physical layout of some components.

Rev 2.3 boards are 100% backward compatible with current versions. No software changes are needed.

- Board size 2.7" x 3.9" (7x10 cm)

- Port A and Port B connector position flipped. Port B now on the left, Port A on the right. Data byte positions remain the same in software.

- Input/Output pads moved .2" back from edge for better DIN rail clearance

      - Solder pad option area pads are .3" and .4" spaced for standard DIP sockets

- Removed center 5V, COM pads.

The IOX32 is an expander which provides an additional 32 lines of i/o for the cpNode using the MCP23017 chip. 
IOX32 lines are configurable in as input or output in 8 bit (1 byte) increments. 
Up to 128 lines of i/o may be added to a cpNode in any combination of IOX16s and IOX32s for a total off 144 lines of i/o.
Input and output voltages are limited to 5V.  Each output may sink up to 25 mA subject to a device limit of 160mA, if all lines are used as output use 10mA as a design limit. 
Since the vast majority of outputs in a model railroad signaling system are for driving LEDS, 10mA should be adequate. 
If you need to work with higher voltages or currents, use the CSNK adapter.  
Pads for inserting limiting resistors are provided for each line.
Output pads are spaced at 0.100" to allow you maximum flexibility in configuring outputs.  

Use the Assembled and Tested (AT) option if you want the IOX32 Assembled and Tested with Screw Terminals for i/o conections

Use the No Header (NH) option if you want the IOX32 Assembled and Tested but want to provide your own 0.100 headers for i/o

Use the Bare Board Option if you want to assemble your own or if you need a 0.100" spacing connector that we don't offer, or contact us for a custom quote for Assembled and Tested units using your favorite connector.

All assembled and tested configurations of the IOX32 include a 6" I2C jumper and 2 address jumpers

The IOX32 draws 10mA @ 5 volts through the (included) I2C expansion cable from the host cpNode.
 
The sch and brd files are not sync'd due to some conversion issues, we expect to issue an updated design with proper Eagle Back Annotation in early 2020