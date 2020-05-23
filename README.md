# Plugin for OctoPrint - displays temperatures on navbar

![NavbarTemp](images/navbar_chamber.png?raw=true) 

Using the T1 pins on my SKR 1.3 board I was able to configure marlin to show chamber temp from a spare 3950 thermister.
You need to define the chamber probe pin like this in your configuration.h thermister settings. The second line has to be added.

#define TEMP_SENSOR_CHAMBER 1
#define TEMP_CHAMBER_PIN TEMP_1_PIN

## Changes in this fork
Added chamber temp to navbar using octoprint chamberTemp variables.
