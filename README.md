# blit7s

v0.0.2 created by Armaan Aggarwal



A python package for RPi.GPIO that allows you to blit characters on a 7 segment unit.

View this package at PyPI at: https://pypi.org/project/blit7s/0.0.2/

### Usage:

**Before you learn about the usage of blit7s:**

***pinlist* is defined as the list of pins of the 7 segment from a-g dp.**
 
 
   ex:
    if a=21,b=22,c=23,d=24,e=25,f=26,g=27,dp=28

   then pinlist=[21,22,23,24,25,26,27,28]
  

  * List of all functions:
  
     * blit7s.blitc(pinlist,character)

     * blit7s.sentence(pinlist,string,pause_time)

     * blit7s.customchr(pinlist,list_of_individual_segments)
     
     * blit7s.chart()
    
 



**Note: blit7s is still in development. The stage of development is currently at alpha.**
