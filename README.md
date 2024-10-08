# cheap-fuse-doctor 

## I'm showing two different high voltage fuses programmers here, they are:

## Number one:

### Resetting the fuses on a Atmel Attiny85 with a Serial High Voltage Programmer ( ... well a frightening 12 volts DC mind you ! )

  Just some pretty printings, to help my failing memory, to an excellent instructable: <a href="https://www.instructables.com/id/Simple-and-cheap-Fuse-Doctor-for-Attiny/">Attiny fuse doctor</a>. 
  
  I just added some code to print-out on the serial port, which Attiny(13, 24, 25, 44, 45, 84 and 85) the Doc has detected.  
  
  Thank's !  
  to https://www.instructables.com/member/diy_bloke/
  
  I like to add stuff like this in Github, just in case it disapears from instructables in this case or from other sources.
  I also added some pictures and fritzing breadboard and schematic views.
    
## Number two:

### Based on new Stuff from:

### https://www.hackster.io/sbinder/attiny85-powered-high-voltage-avr-programmer-3324e1
  
  This is the simplest fuse programmer I ran into, so far. Instead of an Arduino it uses an Attiny85 as a master fuses programmer. I initially had issues with it, but it now works fine after I added 10 uF and a 0.1 uF between +5 and ground, as suggested by the author. I also added a 1K resistor on the base of the transistor. This version is showned in all FuseDoctor_Master_Attiny85 files and a copy of it's .ino file in AttinyMaster-Target.ino.txt.
  
  enjoy !
