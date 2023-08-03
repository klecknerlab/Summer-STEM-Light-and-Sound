This document contains the information you need to construct the basic experiments used for this course.  We assume you have access to basic tools like soldering irons, allen keys, etc.  (This course is run at UC Merced by an experimental physics professor who has all of these items in his lab.)  We also use a 3D printer and laser cutter to fabricate some of the items.  There are definitely other ways to do this; if you bulid these experiments using alternative methods please let us know!  We would be happy to include alternatives here for other instructions.

A spreadsheet of the components required is available here: [components.xlsx](construction/components.xlsx)

# Experimental Rail

The experiments are conducted on a 20x40 mm T-slot railing.  To make this, we purchase (1) 6' 20x40mm and (2) 1' 20x20mm railing per group.  The 1' rails act as legs; to attach them to the 6' rail you drill a hole in the center of each 1' rail.  You can then screw this into the 6' rail using a T-slot nut and screw.  (The hole in the 1' rail is used to insert an allen key to tighten the bolt.)  We then use T-slot nuts to attach rubber bumpers to the each end of the 1' rails.  We also attach end caps to the 1' rails to prevent students from cutting themselves on the sharp edges.  (Unfortunately you can't do this on the ends of the long rails, as they need to insert the mounts there.)

We also attach an adhesive ruler to the middle of the railing.  This is used to measure distances in the experiments.

> **Note:** There are commercial rail systems designed for intro physics experiments, but these are far more expensive than our DIY option.  However, if you have them available it should be possible to adapt the mounts for these.

# Rail Mounts

We 3D printed mounts which let us attach ultrasonic transducers and/or mirror mounts to the experimental rail.  The 3D printer files for these can be found in the *construction* folder.  They will likely require some sanding to fit nicely on the railings.  The mirror mount bracket has a slot to insert an 8-32 nut, which can then be used to screw in a commercial mirror mount (such as the Thorlabs one listed in the materials).

The wavelength of light measurement requires an additional bracket which is laser cut in several pieces from 1/8" acrylic.  These can be glued together using either hot glue or a proper acrylic adhesive.  A rule is then printed out and attached to the bracket with double side tape.  Although it is tempting to laser engrave the rulings on there directly, this doesn't work as well.  (The lines won't be as dark; it will generate laser reflections which could be dangerous, and the UV laser shows up very will on printer paper because it contains UV excited fluorescent whitening agents.)

# Optics Mounts

The optics are mounted in standard 1" mirror mounts.  In order to adapt the laser diodes, photodiodes, laser pointers, and LEDs, we laser cut mounts from 1/4" acrylic.  The drawings we used are found in the *construction* folder.  Note that the sizing of the middle holes may need to be slightly adjusted to give a tight fit.  There is also an oddly shaped ring which is used to hold down the button on the laser pointer.  (It is basically a cam; you slide it over the button and rotate it to depress the button.)  Hot glue can be used to hold items onto the mounts, especially the laser pointers.  This is secure enough, and they can be pried free if needed.

# Electronics

Most of the electronics can be used as-is, but it can be helpful to solder leads onto some things to make it easier to connect.  This is particularly useful for the photdiode, but unfortunately we have found that the listed photodiodes are prone to failure, presumably from soldering induced damage (its also possible that we got a bad batch!).  In this case they can be glued or double-side-taped to the backside of clear acrylic.  (If you have UV cure optical epoxy handy this works wonderfully!)  This leaves the leads exposed, and then you can use jumper wire test leads to connect to a breadboard.

We also solder a 100 Ohm resistor directly to the positive (long) wire of the LED to make it easier to use.  This way they can connect alligator clips directly from the function generator to get it to light up.  The same thing works with the laser diodes; cheap laser diodes use a simple resistor as the current regulation.  This is actually super useful for our purposes; such a simple setup can modulate the laser at several MHz!

> **Note:** Don't be tempted to by "nicer" laser diodes; complicated driver circuits will smooth the input voltage and prevent rapid modulation!