# cheap-fuse-doctor  

### Resetting the fuses on a Atmel Attiny85 with a Serial High Voltage ( ... well a frightening 12 volts mind you ! ) Programmer
  Just some pretty printings, to help my failing memory, to an excellent instructable: <a href="https://www.instructables.com/id/Simple-and-cheap-Fuse-Doctor-for-Attiny/">Attiny fuse doctor</a>. I just added code to print-out on the serial port, which Attiny(13, 24, 25, 44, 45, 84 and 85) the doc. has detected.  
  
  Thank's !  
  to https://www.instructables.com/member/diy_bloke/
  
  I like to add stuff like this in Gethub, just in case it disapears from instructables in this case or from other sources.
  I also added some pictures and fritzing breadboard and schematic views.
    


### New Stuff: from https://www.hackster.io/sbinder/attiny85-powered-high-voltage-avr-programmer-3324e1
  
  This is the simplest fuse programmer so far, instead of an Arduino it uses an Attiny85 as a master fuse programmer. I had issues with it, but it now works fine after I added 10 uF and a 0.1 uF between +5 and ground, as suggested by the author. I also added a 1K resistor on the base of the transistor. You can see my version at: https://github.com/jeanrocco/cheap-fuse-doctor/blob/master/FuseDoctor_Master_Attiny85.fzz , with a copy of the .ino code included.
  
  enjoy !
