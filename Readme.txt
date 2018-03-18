                             _      _ _
                            | |    (_) |
   ___ _ __ ___   ___  _ __ | |     _| |__
  / _ \ '_ ` _ \ / _ \| '_ \| |    | | '_ \
 |  __/ | | | | | (_) | | | | |____| | |_) |
  \___|_| |_| |_|\___/|_| |_|______|_|_.__/

Arduino Energy Monitoring Library - compatible with Arduino 1.0
*****************************************************************

** This fork slip big class method in smallers, this permit to split operation in different time : config, measure, calc, display...
It permit to update the pin number by config request from the Serial. This permit to include it in a config menu without open code to change pinout.
This version is used in the windlogger project.

Designed for use with emonTx: http://openenergymonitor.org/emon/Modules

Download to Arduino IDE 'libraries' folder. Restart of IDE required.

Git Clone and Git Pull can be easily used to keep the library up-to-date and manage changes.
JeeLabs has done a good post on the topic: http://jeelabs.org/2011/12/29/out-with-the-old-in-with-the-new/



Update: 5th January 2014: Support Added for Arduino Due (ARM Cortex-M3, 12-bit ADC) by icboredman.

To enable this feature on Arduino Due, add the following statement to setup() function in main sketch:
analogReadResolution(ADC_BITS); This will set ADC_BITS to 12 (Arduino Due), EmonLib will otherwise default to 10 analogReadResolution(ADC_BITS);.
See blog post on using Arduino Due as energy monitor: http://boredomprojects.net/index.php/projects/home-energy-monitor

