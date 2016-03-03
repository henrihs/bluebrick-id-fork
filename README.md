# bluebrick-id-fork
A fork of [Alban Nanty's BlueBrick](http://bluebrick.lswproject.com/), version 1.8.1.

### What differs
from the original version, is that the brick's unique ID's are generated the first they are drag'n'dropped into the Map. 
The ID is generated the same way as in Alban's version, i.e. by creating a hash code of the initialized object.
The next time the Map is loaded from the *.bbm file, the ID of each brick is read from the xml.

When hovering over a brick (in the actual layer where the brick resides), the unique ID is shown in the status bar.

This software is licensed according to the terms in GPL v.3
